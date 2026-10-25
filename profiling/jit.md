
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.10% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.24% | `[JIT]` | `jit` | jit |
| 2.98% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.74% | `python` | `gc_collect_main` | gc |
| 2.50% | `python` | `_PyObject_Malloc` | memory |
| 1.82% | `python` | `sre_ucs1_match` | library |
| 1.77% | `python` | `_Py_dict_lookup` | lookup |
| 1.70% | `python` | `visit_decref` | gc |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.50% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.40% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.24% | `python` | `visit_reachable` | gc |
| 1.07% | `python` | `tuple_dealloc` | memory |
| 1.00% | `python` | `py_dealloc` | memory |
| 0.81% | `python` | `r_object` | import |
| 0.75% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.71% | `python` | `initialize_locals` | interpreter |
| 0.67% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.65% | `python` | `_PyCode_Quicken` | interpreter |
| 0.63% | `python` | `_Py_Dealloc` | memory |
| 0.62% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.60% | `python` | `tuple_alloc` | memory |
| 0.57% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.57% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.55% | `python` | `find_name_in_mro` | lookup |
| 0.53% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.50% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.48% | `python` | `dict_traverse` | gc |
| 0.43% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.41% | `python` | `siphash13` | str |
| 0.41% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.40% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.40% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.36% | `python` | `insertdict` | dict |
| 0.36% | `python` | `type_ready` | dynamic |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.34% | `python` | `PyDict_GetItemRef` | dict |
| 0.33% | `python` | `gen_dealloc` | memory |
| 0.33% | `libc.so.6` | `_int_malloc` | libc |
| 0.33% | `python` | `PyObject_SetAttr` | dynamic |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.31% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.30% | `python` | `_PyEval_Vector` | interpreter |
| 0.29% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.29% | `python` | `update_one_slot` | lookup |
| 0.29% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.28% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.27% | `python` | `intern_constants` | str |
| 0.27% | `python` | `list_subscript` | list |
| 0.26% | `python` | `dict_dealloc` | memory |
| 0.26% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.25% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.25% | `python` | `insert_to_emptydict` | dict |

## argparse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.49% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.84% | `[JIT]` | `jit` | jit |
| 2.72% | `python` | `_PyObject_Malloc` | memory |
| 2.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.24% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.63% | `python` | `_Py_dict_lookup` | lookup |
| 1.58% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.57% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `initialize_locals` | interpreter |
| 0.91% | `python` | `py_dealloc` | memory |
| 0.85% | `python` | `_Py_Dealloc` | memory |
| 0.82% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.78% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.78% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.75% | `python` | `tuple_dealloc` | memory |
| 0.67% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.65% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.64% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.63% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.56% | `python` | `gc_collect_main` | gc |
| 0.55% | `python` | `PyUnicode_Format` | str |
| 0.50% | `python` | `PyDict_GetItemRef` | dict |
| 0.48% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.48% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.47% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.45% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.45% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.45% | `python` | `PyList_New.constprop.0` | memory |
| 0.45% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.42% | `python` | `insertdict` | dict |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.41% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.40% | `python` | `PyType_IsSubtype` | dynamic |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.39% | `python` | `tuple_alloc` | memory |
| 0.39% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.39% | `libc.so.6` | `__gconv_transform_utf8_internal` | libc |
| 0.37% | `python` | `PyUnicode_Contains` | str |
| 0.37% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.37% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.37% | `python` | `dict_dealloc` | memory |
| 0.37% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.34% | `python` | `replace` | str |
| 0.33% | `python` | `new_dict.constprop.0` | dict |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `_PyObject_Realloc` | memory |
| 0.32% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.31% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.31% | `libc.so.6` | `malloc` | libc |
| 0.31% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.29% | `python` | `sre_ucs1_match` | library |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `PyObject_Call` | dynamic |
| 0.28% | `python` | `PyUnicode_New.part.0` | memory |
| 0.27% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `siphash13` | str |
| 0.26% | `python` | `PyUnicode_Append` | str |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `split` | str |

## argparse_subparsers

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.14% | `[JIT]` | `jit` | jit |
| 9.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.76% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.13% | `python` | `_PyObject_Malloc` | memory |
| 2.77% | `python` | `_PyObject_Free` | memory |
| 2.67% | `python` | `_Py_dict_lookup` | lookup |
| 2.30% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.22% | `python` | `initialize_locals` | interpreter |
| 1.99% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.44% | `python` | `gc_collect_main` | gc |
| 1.04% | `python` | `py_dealloc` | memory |
| 0.98% | `libc.so.6` | `_int_malloc` | libc |
| 0.93% | `python` | `long_to_decimal_string_internal` | int |
| 0.92% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.92% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.88% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.73% | `python` | `_Py_Dealloc` | memory |
| 0.70% | `python` | `tuple_dealloc` | memory |
| 0.66% | `python` | `insertdict` | dict |
| 0.65% | `python` | `visit_decref` | gc |
| 0.63% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.62% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.62% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.61% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.61% | `python` | `tuple_alloc` | memory |
| 0.56% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.56% | `python` | `sre_ucs1_match` | library |
| 0.55% | `python` | `PyUnicode_Contains` | str |
| 0.54% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.53% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.52% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 0.51% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.47% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.47% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.47% | `python` | `list_dealloc` | memory |
| 0.46% | `python` | `PyUnicode_Format` | str |
| 0.46% | `python` | `PyObject_Str` | dynamic |
| 0.46% | `python` | `pattern_new_match` | memory |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.43% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.41% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.40% | `python` | `_PyJIT_Entry` | compiler |
| 0.39% | `python` | `_PyEval_Vector` | interpreter |
| 0.38% | `python` | `_PyDict_Subscript` | dict |
| 0.37% | `python` | `dict_get` | dict |
| 0.36% | `python` | `unicode_dealloc` | memory |
| 0.36% | `python` | `PyType_IsSubtype` | dynamic |
| 0.35% | `libc.so.6` | `malloc` | libc |
| 0.35% | `python` | `siphash13` | str |
| 0.34% | `python` | `PyThread_get_thread_ident` | threading |
| 0.34% | `python` | `PyDict_Contains` | dict |
| 0.33% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.32% | `python` | `_Py_NewReference` | memory |
| 0.31% | `python` | `set_add_entry_takeref` | miscobj |
| 0.31% | `python` | `PyUnicode_New.part.0` | memory |
| 0.31% | `python` | `clone_combined_dict_keys` | unknown |
| 0.30% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.30% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.30% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.29% | `python` | `PyDict_GetItemRef` | dict |
| 0.29% | `python` | `visit_reachable` | gc |
| 0.29% | `python` | `insert_to_emptydict` | dict |
| 0.29% | `python` | `PyMethod_New` | memory |
| 0.28% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.28% | `python` | `PyList_New.constprop.0` | memory |
| 0.28% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.27% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.27% | `python` | `PyDict_Next` | dict |
| 0.26% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.25% | `python` | `subtype_traverse` | gc |
| 0.25% | `python` | `dict_dealloc` | memory |
| 0.25% | `python` | `dict_merge` | dict |
| 0.25% | `python` | `_PyObject_GC_New` | gc |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.19% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.10% | `[JIT]` | `jit` | jit |
| 5.14% | `python` | `_PyAsyncGenASend_Send` | unknown |
| 3.82% | `python` | `py_dealloc` | memory |
| 3.65% | `python` | `async_gen_anext` | async |
| 2.72% | `python` | `async_gen_asend_dealloc` | memory |
| 2.17% | `python` | `_Py_Dealloc` | memory |
| 2.01% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.92% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.60% | `python` | `gc_collect_main` | gc |
| 1.60% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.57% | `python` | `_PyObject_Free` | memory |
| 1.45% | `python` | `_PyJIT_Entry` | compiler |
| 1.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.29% | `python` | `initialize_locals` | interpreter |
| 1.21% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 1.13% | `python` | `_Py_NewReference` | memory |
| 1.06% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.01% | `python` | `visit_reachable` | gc |
| 0.95% | `python` | `visit_decref` | gc |
| 0.95% | `python` | `make_range_object` | unknown |
| 0.89% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.87% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.75% | `python` | `range_subscript` | miscobj |
| 0.74% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.69% | `python` | `_PyEval_GetANext` | interpreter |
| 0.69% | `python` | `PyNumber_Add` | dynamic |
| 0.68% | `python` | `_PyEval_Vector` | interpreter |
| 0.67% | `python` | `_PyLong_FromMedium` | int |
| 0.64% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.63% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.62% | `python` | `subtype_traverse` | gc |
| 0.60% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.57% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.56% | `python` | `long_add_method` | int |
| 0.55% | `python` | `long_richcompare` | int |
| 0.54% | `python` | `PySlice_New` | memory |
| 0.54% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.53% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.48% | `python` | `PyType_GenericAlloc` | memory |
| 0.46% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.42% | `python` | `set_add_entry_takeref` | miscobj |
| 0.40% | `python` | `gen_dealloc` | memory |
| 0.36% | `python` | `range_dealloc` | memory |
| 0.35% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.35% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.30% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.29% | `python` | `long_dealloc` | memory |
| 0.28% | `python` | `long_mul` | int |
| 0.28% | `python` | `weakref_ref_vectorcall` | miscobj |
| 0.28% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.28% | `python` | `set_lookkey` | miscobj |
| 0.28% | `python` | `long_div` | int |
| 0.27% | `python` | `PyObject_GetItem` | dynamic |
| 0.27% | `python` | `_PyObject_GC_Link` | gc |
| 0.25% | `python` | `PyLong_FromLong` | int |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.83% | `[JIT]` | `jit` | jit |
| 6.71% | `python` | `gc_collect_main` | gc |
| 6.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.40% | `python` | `visit_reachable` | gc |
| 4.86% | `python` | `visit_decref` | gc |
| 3.30% | `python` | `_PyObject_Malloc` | memory |
| 2.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.07% | `python` | `_PyObject_Free` | memory |
| 1.97% | `python` | `initialize_locals` | interpreter |
| 1.68% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.45% | `python` | `subtype_traverse` | gc |
| 1.11% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.07% | `python` | `context_tp_dealloc` | memory |
| 1.06% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.06% | `python` | `py_dealloc` | memory |
| 1.04% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.90% | `python` | `_PyEval_Vector` | interpreter |
| 0.88% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.82% | `python` | `_Py_Dealloc` | memory |
| 0.76% | `python` | `TaskObj_traverse` | gc |
| 0.69% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.61% | `python` | `clear_slots` | unknown |
| 0.59% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.57% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.56% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.50% | `python` | `_PyMember_GetOffset` | unknown |
| 0.50% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.48% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.47% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.45% | `python` | `_PyJIT_Entry` | compiler |
| 0.45% | `python` | `_Py_dict_lookup` | lookup |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.45% | `python` | `PyUnicode_RichCompare` | str |
| 0.44% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.44% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.43% | `python` | `_PyObject_Realloc` | memory |
| 0.41% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.41% | `python` | `_PyObject_GC_New` | gc |
| 0.39% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.39% | `python` | `TaskObj_clear` | unknown |
| 0.38% | `python` | `insert_to_emptydict` | dict |
| 0.38% | `python` | `context_tp_traverse` | gc |
| 0.38% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.38% | `python` | `_PyObject_Calloc` | memory |
| 0.38% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.37% | `python` | `gen_dealloc` | memory |
| 0.37% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.37% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.36% | `python` | `context_run` | unknown |
| 0.34% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.34% | `python` | `PyObject_GC_Del` | gc |
| 0.33% | `python` | `_Py_NewReference` | memory |
| 0.33% | `python` | `gen_traverse` | gc |
| 0.33% | `python` | `PyIter_Send` | dynamic |
| 0.32% | `python` | `PyCMethod_New` | memory |
| 0.32% | `python` | `PyObject_Call` | dynamic |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.30% | `python` | `subtype_dealloc` | memory |
| 0.30% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.29% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.29% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.29% | `python` | `task_step_impl` | unknown |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `_asyncio_Task___init__` | unknown |
| 0.27% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.26% | `python` | `PyDict_GetItemRef` | dict |
| 0.26% | `python` | `list_extend_lock_held` | list |
| 0.26% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.25% | `python` | `list_traverse` | gc |
| 0.25% | `python` | `_PyObject_GC_NewVar` | gc |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.24% | `python` | `k_mul` | int |
| 8.43% | `[JIT]` | `jit` | jit |
| 5.01% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.20% | `python` | `_PyObject_Malloc` | memory |
| 4.04% | `python` | `gc_collect_main` | gc |
| 3.33% | `python` | `visit_reachable` | gc |
| 3.19% | `python` | `_PyObject_Free` | memory |
| 3.06% | `python` | `visit_decref` | gc |
| 2.80% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.66% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.57% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.45% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.19% | `python` | `PyThread_get_thread_ident` | threading |
| 1.14% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.11% | `python` | `initialize_locals` | interpreter |
| 1.00% | `python` | `subtype_traverse` | gc |
| 0.90% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.87% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.83% | `python` | `_Py_IsMainThread` | unknown |
| 0.74% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.64% | `python` | `_Py_Dealloc` | memory |
| 0.62% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.61% | `python` | `_PyEval_Vector` | interpreter |
| 0.60% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.59% | `python` | `context_tp_dealloc` | memory |
| 0.59% | `python` | `PyNumber_Multiply` | dynamic |
| 0.56% | `python` | `py_dealloc` | memory |
| 0.54% | `python` | `long_mul` | int |
| 0.47% | `python` | `long_alloc` | memory |
| 0.44% | `python` | `long_lshift1` | int |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.35% | `python` | `TaskObj_traverse` | gc |
| 0.35% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.35% | `python` | `_PyMember_GetOffset` | unknown |
| 0.34% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.33% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.31% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.31% | `python` | `_Py_dict_lookup` | lookup |
| 0.30% | `python` | `clear_slots` | unknown |
| 0.29% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.29% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.28% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.28% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `pthread_self@plt` | unknown |
| 0.28% | `python` | `long_dealloc` | memory |
| 0.26% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.26% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.25% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.25% | `python` | `tuple_dealloc` | memory |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.80% | `python` | `k_mul` | int |
| 8.48% | `[JIT]` | `jit` | jit |
| 4.93% | `python` | `gc_collect_main` | gc |
| 4.51% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.23% | `python` | `_PyObject_Malloc` | memory |
| 3.74% | `python` | `visit_reachable` | gc |
| 3.38% | `python` | `visit_decref` | gc |
| 3.24% | `python` | `_PyObject_Free` | memory |
| 2.70% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.62% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.58% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.39% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 1.19% | `python` | `PyThread_get_thread_ident` | threading |
| 1.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.93% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.90% | `python` | `subtype_traverse` | gc |
| 0.82% | `python` | `initialize_locals` | interpreter |
| 0.78% | `python` | `_Py_IsMainThread` | unknown |
| 0.77% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.76% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.70% | `python` | `_Py_Dealloc` | memory |
| 0.70% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.67% | `python` | `py_dealloc` | memory |
| 0.61% | `python` | `_PyEval_Vector` | interpreter |
| 0.60% | `python` | `PyNumber_Multiply` | dynamic |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.52% | `python` | `long_mul` | int |
| 0.47% | `python` | `long_alloc` | memory |
| 0.47% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.45% | `python` | `long_lshift1` | int |
| 0.43% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.40% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.40% | `python` | `TaskObj_traverse` | gc |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `_PyMember_GetOffset` | unknown |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.33% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.31% | `python` | `_PyInterpreterState_GetConfig` | unknown |
| 0.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.30% | `libc.so.6` | `__GI___pthread_self` | libc |
| 0.29% | `python` | `set_traverse` | gc |
| 0.29% | `python` | `clear_slots` | unknown |
| 0.28% | `python` | `_PyInterpreterState_Main` | unknown |
| 0.28% | `python` | `gen_traverse` | gc |
| 0.27% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.26% | `_math_integer.cpython-316-x86_64-linux-gnu.so` | `math_integer_factorial` | library |
| 0.26% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.26% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.26% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.26% | `python` | `gen_dealloc` | memory |
| 0.25% | `python` | `long_dealloc` | memory |
| 0.25% | `python` | `pthread_self@plt` | unknown |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 12.77% | `[JIT]` | `jit` | jit |
| 10.48% | `python` | `gc_collect_main` | gc |
| 8.66% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.15% | `python` | `visit_reachable` | gc |
| 6.80% | `python` | `visit_decref` | gc |
| 2.31% | `python` | `_PyObject_Malloc` | memory |
| 1.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.87% | `python` | `subtype_traverse` | gc |
| 1.83% | `python` | `initialize_locals` | interpreter |
| 1.38% | `python` | `_PyObject_Free` | memory |
| 1.34% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.31% | `python` | `_PyEval_Vector` | interpreter |
| 1.30% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.01% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.87% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.85% | `python` | `py_dealloc` | memory |
| 0.78% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.71% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.66% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.65% | `python` | `_PyMember_GetOffset` | unknown |
| 0.62% | `python` | `slot_tp_richcompare` | dynamic |
| 0.59% | `python` | `_Py_Dealloc` | memory |
| 0.57% | `python` | `_PyJIT_Entry` | compiler |
| 0.56% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.56% | `python` | `gen_traverse` | gc |
| 0.50% | `python` | `TaskObj_traverse` | gc |
| 0.49% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.47% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.45% | `python` | `clear_slots` | unknown |
| 0.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.40% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.40% | `python` | `_PyObject_Realloc` | memory |
| 0.38% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.38% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.37% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.36% | `python` | `gen_dealloc` | memory |
| 0.35% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.35% | `python` | `context_tp_dealloc` | memory |
| 0.34% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.32% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.32% | `python` | `_PyObject_Calloc` | memory |
| 0.32% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `_Py_dict_lookup` | lookup |
| 0.31% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.30% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.30% | `python` | `list_traverse` | gc |
| 0.29% | `python` | `FutureObj_traverse` | gc |
| 0.28% | `python` | `context_tp_traverse` | gc |
| 0.28% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.28% | `python` | `PyCMethod_New` | memory |
| 0.27% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `PyDict_GetItemRef` | dict |
| 0.26% | `python` | `list_extend_lock_held` | list |
| 0.25% | `python` | `tuple_traverse` | gc |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.97% | `[JIT]` | `jit` | jit |
| 11.70% | `python` | `gc_collect_main` | gc |
| 8.85% | `python` | `visit_reachable` | gc |
| 8.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.31% | `python` | `visit_decref` | gc |
| 2.30% | `python` | `_PyObject_Malloc` | memory |
| 1.90% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.72% | `python` | `subtype_traverse` | gc |
| 1.62% | `python` | `initialize_locals` | interpreter |
| 1.61% | `python` | `_PyEval_Vector` | interpreter |
| 1.32% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.27% | `python` | `_PyObject_Free` | memory |
| 1.25% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.22% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.96% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.90% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.89% | `python` | `py_dealloc` | memory |
| 0.83% | `_heapq.cpython-316-x86_64-linux-gnu.so` | `siftup` | library |
| 0.75% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `gen_traverse` | gc |
| 0.67% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.64% | `python` | `_Py_Dealloc` | memory |
| 0.62% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.58% | `python` | `slot_tp_richcompare` | dynamic |
| 0.58% | `python` | `_PyMember_GetOffset` | unknown |
| 0.56% | `python` | `TaskObj_traverse` | gc |
| 0.51% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.50% | `python` | `_PyJIT_Entry` | compiler |
| 0.49% | `python` | `clear_slots` | unknown |
| 0.47% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.45% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.44% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.43% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.42% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.40% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.38% | `python` | `set_traverse` | gc |
| 0.37% | `python` | `gen_dealloc` | memory |
| 0.36% | `python` | `tuple_dealloc` | memory |
| 0.36% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.33% | `python` | `_PyObject_Calloc` | memory |
| 0.31% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.30% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.30% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `python` | `_PyObject_Realloc` | memory |
| 0.29% | `python` | `PyObject_Call` | dynamic |
| 0.29% | `python` | `FutureObj_traverse` | gc |
| 0.27% | `python` | `context_tp_traverse` | gc |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `python` | `PyCMethod_New` | memory |
| 0.26% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.25% | `python` | `list_extend_lock_held` | list |
| 0.25% | `python` | `tuple_alloc` | memory |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.65% | `[JIT]` | `jit` | jit |
| 8.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.45% | `python` | `gc_collect_main` | gc |
| 6.01% | `python` | `visit_reachable` | gc |
| 5.68% | `python` | `visit_decref` | gc |
| 3.07% | `python` | `_PyObject_Malloc` | memory |
| 2.07% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.90% | `python` | `initialize_locals` | interpreter |
| 1.80% | `python` | `subtype_traverse` | gc |
| 1.72% | `python` | `_PyObject_Free` | memory |
| 1.42% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.11% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.11% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.09% | `python` | `_PyEval_Vector` | interpreter |
| 0.99% | `python` | `context_tp_dealloc` | memory |
| 0.98% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.98% | `python` | `py_dealloc` | memory |
| 0.74% | `python` | `_Py_Dealloc` | memory |
| 0.63% | `python` | `TaskObj_traverse` | gc |
| 0.61% | `python` | `_PyMember_GetOffset` | unknown |
| 0.61% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.61% | `python` | `_Py_dict_lookup` | lookup |
| 0.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.52% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.51% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.47% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.47% | `python` | `_PyJIT_Entry` | compiler |
| 0.47% | `python` | `clear_slots` | unknown |
| 0.43% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.43% | `python` | `tuple_dealloc` | memory |
| 0.42% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.42% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.41% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.40% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.39% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.39% | `python` | `_PyObject_Realloc` | memory |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.38% | `python` | `PyUnicode_RichCompare` | str |
| 0.37% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.37% | `python` | `PyIter_Send` | dynamic |
| 0.36% | `python` | `TaskObj_clear` | unknown |
| 0.36% | `python` | `gen_dealloc` | memory |
| 0.35% | `python` | `list_extend_lock_held` | list |
| 0.35% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.34% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.33% | `python` | `context_run` | unknown |
| 0.33% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.32% | `python` | `insert_to_emptydict` | dict |
| 0.32% | `python` | `gen_traverse` | gc |
| 0.31% | `python` | `_PyObject_Calloc` | memory |
| 0.31% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.31% | `python` | `subtype_dealloc` | memory |
| 0.31% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `context_tp_traverse` | gc |
| 0.30% | `python` | `PyCMethod_New` | memory |
| 0.30% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.29% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.29% | `python` | `_PyType_GetDict` | dynamic |
| 0.29% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.28% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.27% | `python` | `list_traverse` | gc |
| 0.27% | `python` | `PyObject_Call` | dynamic |
| 0.27% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.27% | `python` | `future_schedule_callbacks` | unknown |
| 0.26% | `python` | `task_step_impl` | unknown |
| 0.26% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.25% | `python` | `PyObject_GC_Del` | gc |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.93% | `[JIT]` | `jit` | jit |
| 9.62% | `python` | `gc_collect_main` | gc |
| 7.21% | `python` | `visit_reachable` | gc |
| 7.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.47% | `python` | `visit_decref` | gc |
| 2.96% | `python` | `_PyObject_Malloc` | memory |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.73% | `python` | `subtype_traverse` | gc |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.47% | `python` | `initialize_locals` | interpreter |
| 1.27% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.15% | `python` | `py_dealloc` | memory |
| 1.12% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.08% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.01% | `python` | `_PyEval_Vector` | interpreter |
| 0.88% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.87% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.83% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.78% | `python` | `_Py_Dealloc` | memory |
| 0.72% | `python` | `TaskObj_traverse` | gc |
| 0.71% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.66% | `python` | `_PyMember_GetOffset` | unknown |
| 0.62% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.54% | `python` | `set_traverse` | gc |
| 0.53% | `python` | `gen_traverse` | gc |
| 0.51% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.47% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.47% | `python` | `clear_slots` | unknown |
| 0.46% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.43% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.41% | `python` | `gen_dealloc` | memory |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.40% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.37% | `python` | `tuple_dealloc` | memory |
| 0.37% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.37% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.36% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.36% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.36% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.36% | `python` | `PyObject_Call` | dynamic |
| 0.35% | `python` | `PyUnicode_RichCompare` | str |
| 0.35% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.33% | `python` | `_PyObject_Calloc` | memory |
| 0.33% | `python` | `context_tp_dealloc` | memory |
| 0.32% | `python` | `set_lookkey` | miscobj |
| 0.31% | `python` | `context_tp_traverse` | gc |
| 0.31% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `TaskObj_clear` | unknown |
| 0.30% | `python` | `subtype_dealloc` | memory |
| 0.30% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.29% | `python` | `tuple_alloc` | memory |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.27% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.25% | `python` | `_Py_dict_lookup` | lookup |
| 0.25% | `python` | `PyIter_Send` | dynamic |
| 0.25% | `python` | `allocate_from_new_pool` | memory |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.91% | `[JIT]` | `jit` | jit |
| 8.13% | `python` | `gc_collect_main` | gc |
| 6.27% | `python` | `visit_reachable` | gc |
| 5.20% | `python` | `visit_decref` | gc |
| 5.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.29% | `python` | `_PyObject_Malloc` | memory |
| 1.91% | `python` | `_PyObject_Free` | memory |
| 1.90% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `initialize_locals` | interpreter |
| 1.33% | `python` | `subtype_traverse` | gc |
| 1.33% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.28% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.28% | `python` | `py_dealloc` | memory |
| 1.22% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.08% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.95% | `python` | `_PyEval_Vector` | interpreter |
| 0.92% | `python` | `_Py_Dealloc` | memory |
| 0.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.84% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.80% | `python` | `_PyGC_VisitFrameStack` | gc |
| 0.75% | `python` | `TaskObj_traverse` | gc |
| 0.69% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.62% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.60% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.60% | `python` | `clear_slots` | unknown |
| 0.59% | `python` | `set_traverse` | gc |
| 0.57% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.53% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.52% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.50% | `python` | `_PyMember_GetOffset` | unknown |
| 0.50% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.49% | `python` | `PyObject_Call` | dynamic |
| 0.49% | `python` | `gen_traverse` | gc |
| 0.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.47% | `python` | `tuple_dealloc` | memory |
| 0.46% | `python` | `subtype_dealloc` | memory |
| 0.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.42% | `python` | `gen_dealloc` | memory |
| 0.41% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.41% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.40% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.40% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.39% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.37% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.37% | `python` | `_PyObject_Calloc` | memory |
| 0.36% | `python` | `PyUnicode_RichCompare` | str |
| 0.35% | `python` | `PyObject_GC_Del` | gc |
| 0.35% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.34% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.32% | `python` | `allocate_from_new_pool` | memory |
| 0.32% | `python` | `context_tp_traverse` | gc |
| 0.32% | `python` | `TaskStepMethWrapper_call` | unknown |
| 0.32% | `python` | `insert_to_emptydict` | dict |
| 0.31% | `python` | `dict_dealloc` | memory |
| 0.31% | `python` | `_Py_NewReference` | memory |
| 0.31% | `python` | `tuple_alloc` | memory |
| 0.30% | `python` | `_PyObject_VectorcallPrepend` | dynamic |
| 0.30% | `python` | `context_run` | unknown |
| 0.29% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.29% | `python` | `PyDict_New` | memory |
| 0.29% | `python` | `PyCMethod_New` | memory |
| 0.29% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `context_tp_dealloc` | memory |
| 0.26% | `python` | `PyList_New` | memory |
| 0.26% | `python` | `_PyType_GetDict` | dynamic |
| 0.26% | `python` | `PyObject_Vectorcall` | dynamic |

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
| 4.83% | `libz.so.1.3` | `0x0000000000008c1c` | library |
| 4.18% | `libz.so.1.3` | `0x0000000000008c20` | library |
| 3.58% | `libz.so.1.3` | `0x0000000000002dda` | library |
| 3.55% | `libz.so.1.3` | `0x0000000000002dce` | library |
| 3.53% | `libz.so.1.3` | `0x0000000000008bf7` | library |
| 3.53% | `libz.so.1.3` | `0x0000000000002de6` | library |
| 3.52% | `libz.so.1.3` | `0x0000000000002dd1` | library |
| 3.51% | `libz.so.1.3` | `0x0000000000002dd6` | library |
| 3.49% | `libz.so.1.3` | `0x0000000000002dc3` | library |
| 2.31% | `libz.so.1.3` | `0x0000000000008192` | library |
| 2.26% | `libz.so.1.3` | `0x0000000000008be6` | library |
| 2.21% | `libz.so.1.3` | `0x00000000000082aa` | library |
| 2.14% | `libz.so.1.3` | `0x0000000000008c25` | library |
| 2.04% | `libz.so.1.3` | `0x0000000000008bed` | library |
| 2.02% | `libz.so.1.3` | `0x0000000000008c2c` | library |
| 2.00% | `libz.so.1.3` | `0x0000000000008bd6` | library |
| 1.93% | `libz.so.1.3` | `0x0000000000008c07` | library |
| 1.91% | `libz.so.1.3` | `0x0000000000008c18` | library |
| 1.80% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.78% | `libz.so.1.3` | `0x00000000000082b7` | library |
| 1.72% | `libz.so.1.3` | `0x000000000000819f` | library |
| 1.39% | `libz.so.1.3` | `0x0000000000008bdf` | library |
| 1.36% | `libz.so.1.3` | `0x0000000000008c2f` | library |
| 1.33% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.31% | `libz.so.1.3` | `0x0000000000008bf1` | library |
| 1.30% | `libz.so.1.3` | `0x0000000000008c0a` | library |
| 1.29% | `libz.so.1.3` | `0x0000000000008bfa` | library |
| 1.11% | `libz.so.1.3` | `0x0000000000008c01` | library |
| 1.03% | `libz.so.1.3` | `0x0000000000008c0e` | library |
| 0.93% | `libz.so.1.3` | `0x0000000000008bd0` | library |
| 0.91% | `libz.so.1.3` | `0x0000000000008267` | library |
| 0.91% | `libz.so.1.3` | `0x0000000000008172` | library |
| 0.91% | `libz.so.1.3` | `0x0000000000008258` | library |
| 0.90% | `libz.so.1.3` | `0x000000000000828a` | library |
| 0.90% | `libz.so.1.3` | `0x0000000000008c2a` | library |
| 0.89% | `libz.so.1.3` | `0x0000000000008140` | library |
| 0.89% | `libz.so.1.3` | `0x000000000000814f` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008161` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008c14` | library |
| 0.88% | `libz.so.1.3` | `0x0000000000008182` | library |
| 0.88% | `libz.so.1.3` | `0x000000000000829a` | library |
| 0.85% | `libz.so.1.3` | `0x0000000000008279` | library |
| 0.65% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.53% | `libz.so.1.3` | `0x0000000000002419` | library |
| 0.52% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.51% | `libz.so.1.3` | `0x000000000000242e` | library |
| 0.50% | `libz.so.1.3` | `0x0000000000002416` | library |
| 0.50% | `libz.so.1.3` | `0x0000000000008be3` | library |
| 0.50% | `libz.so.1.3` | `0x0000000000008196` | library |
| 0.49% | `libz.so.1.3` | `0x0000000000008c37` | library |
| 0.47% | `libz.so.1.3` | `0x0000000000008c28` | library |
| 0.47% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.47% | `libz.so.1.3` | `0x00000000000023f4` | library |
| 0.47% | `libz.so.1.3` | `0x00000000000082ae` | library |
| 0.45% | `libz.so.1.3` | `0x0000000000008bfe` | library |
| 0.39% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.36% | `libz.so.1.3` | `0x0000000000002403` | library |
| 0.35% | `libz.so.1.3` | `0x000000000000829e` | library |
| 0.35% | `libz.so.1.3` | `0x000000000000828e` | library |
| 0.35% | `libz.so.1.3` | `0x000000000000827d` | library |
| 0.34% | `libz.so.1.3` | `0x000000000000826c` | library |
| 0.34% | `libz.so.1.3` | `0x00000000000082bb` | library |
| 0.33% | `libz.so.1.3` | `0x0000000000008144` | library |
| 0.33% | `libz.so.1.3` | `0x000000000000825c` | library |
| 0.32% | `libz.so.1.3` | `0x00000000000081a3` | library |
| 0.32% | `libz.so.1.3` | `0x0000000000008154` | library |
| 0.31% | `libz.so.1.3` | `0x0000000000008176` | library |
| 0.30% | `libz.so.1.3` | `0x0000000000008165` | library |
| 0.29% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.29% | `libz.so.1.3` | `0x0000000000008186` | library |
| 0.26% | `libz.so.1.3` | `0x00000000000023f0` | library |

## base64

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 10.81% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base85` | library |
| 7.59% | `[JIT]` | `jit` | jit |
| 7.56% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base64` | library |
| 7.48% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_ascii85` | library |
| 6.57% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base64` | library |
| 5.46% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 5.15% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_base32` | library |
| 3.85% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base32` | library |
| 3.74% | `python` | `_PyArg_UnpackKeywords` | calls |
| 3.44% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_base85` | library |
| 2.84% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_b2a_ascii85` | library |
| 2.52% | `python` | `initialize_locals` | interpreter |
| 2.15% | `python` | `_Py_bytes_upper` | unknown |
| 2.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.82% | `python` | `PyDict_GetItemRef` | dict |
| 1.59% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.59% | `python` | `_PyObject_Malloc` | memory |
| 1.56% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 1.48% | `python` | `_Py_dict_lookup` | lookup |
| 1.41% | `python` | `_PyObject_Free` | memory |
| 1.31% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.07% | `python` | `PyBytesWriter_Create` | unknown |
| 1.02% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.86% | `python` | `bytes_translate_impl` | str |
| 0.75% | `libc.so.6` | `__memchr_avx2` | libc |
| 0.72% | `python` | `PyBytesWriter_FinishWithPointer` | unknown |
| 0.67% | `python` | `PyBuffer_FillInfo` | miscobj |
| 0.65% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.65% | `python` | `PyBuffer_Release` | miscobj |
| 0.63% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.56% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.46% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS` | calls |
| 0.46% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.45% | `python` | `bytes_alloc` | memory |
| 0.44% | `python` | `_Py_strhex_impl` | unknown |
| 0.38% | `python` | `PyObject_IsInstance` | dynamic |
| 0.38% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.33% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.31% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.29% | `python` | `_PyLong_Size_t_Converter` | int |
| 0.28% | `python` | `object_isinstance` | dynamic |
| 0.27% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.27% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.26% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.25% | `python` | `PyObject_IsTrue` | dynamic |

## bpe_tokeniser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.27% | `[JIT]` | `jit` | jit |
| 4.88% | `python` | `_Py_dict_lookup` | lookup |
| 4.22% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.13% | `python` | `py_dealloc` | memory |
| 3.78% | `python` | `tuple_dealloc` | memory |
| 2.77% | `python` | `list_dealloc` | memory |
| 2.73% | `python` | `_PyObject_Free` | memory |
| 2.39% | `python` | `tuple_alloc` | memory |
| 2.23% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 2.19% | `python` | `_PyObject_Malloc` | memory |
| 2.16% | `python` | `gc_collect_main` | gc |
| 2.03% | `python` | `listiter_next` | list |
| 1.83% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.78% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.64% | `python` | `_Py_Dealloc` | memory |
| 1.45% | `python` | `PyList_New.constprop.0` | memory |
| 1.39% | `python` | `PyTuple_New` | memory |
| 1.38% | `python` | `zip_next` | unknown |
| 1.34% | `python` | `visit_decref` | gc |
| 1.32% | `python` | `visit_reachable` | gc |
| 1.26% | `python` | `list_traverse` | gc |
| 1.24% | `python` | `list_slice_lock_held` | list |
| 1.21% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.16% | `python` | `tuple_richcompare` | tuple |
| 1.15% | `python` | `list_iter` | list |
| 1.14% | `python` | `tuple_hash` | tuple |
| 0.98% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.93% | `python` | `_PyCompactLong_Add` | unknown |
| 0.90% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.88% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.84% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.80% | `python` | `_Py_NewReference` | memory |
| 0.78% | `python` | `insertdict` | dict |
| 0.76% | `python` | `PyArg_UnpackTuple` | calls |
| 0.70% | `python` | `zip_new` | memory |
| 0.70% | `python` | `listiter_dealloc` | memory |
| 0.67% | `python` | `_PyDict_Subscript` | dict |
| 0.67% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.62% | `python` | `wrapperdescr_call` | unknown |
| 0.59% | `python` | `PyObject_Hash` | dynamic |
| 0.53% | `python` | `PyLong_FromSsize_t` | int |
| 0.52% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.51% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.51% | `python` | `dictiter_iternextkey` | dict |
| 0.48% | `python` | `_PyEval_Vector` | interpreter |
| 0.46% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.44% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.44% | `python` | `initialize_locals` | interpreter |
| 0.44% | `python` | `_PyJIT_Entry` | compiler |
| 0.43% | `python` | `PyObject_RichCompare` | dynamic |
| 0.43% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.43% | `python` | `_PyList_BinarySlice` | list |
| 0.42% | `python` | `PyType_GenericAlloc` | memory |
| 0.41% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.39% | `python` | `bytes_richcompare` | str |
| 0.39% | `python` | `_PyDict_StoreSubscript` | dict |
| 0.39% | `python` | `PySlice_Unpack` | miscobj |
| 0.38% | `python` | `zip_dealloc` | memory |
| 0.36% | `python` | `_PyObject_Realloc` | memory |
| 0.35% | `python` | `wrap_objobjargproc` | unknown |
| 0.35% | `python` | `_PyObject_GC_New` | gc |
| 0.34% | `python` | `PyObject_Size` | dynamic |
| 0.33% | `python` | `PyObject_GetIter` | dynamic |
| 0.31% | `python` | `PyObject_SetItem` | dynamic |
| 0.31% | `python` | `_PyList_SliceSubscript` | list |
| 0.31% | `python` | `list_slice_wrap` | list |
| 0.30% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.30% | `python` | `_PyObject_RealIsSubclass` | dynamic |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.28% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.28% | `python` | `type_call` | dynamic |
| 0.27% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.27% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.25% | `python` | `_PyObject_GC_Link` | gc |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.96% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.41% | `[JIT]` | `jit` | jit |
| 3.60% | `python` | `_PyObject_Malloc` | memory |
| 3.38% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.08% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.80% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 2.29% | `python` | `_PyObject_Free` | memory |
| 1.93% | `python` | `long_to_decimal_string_internal` | int |
| 1.83% | `python` | `_Py_dict_lookup` | lookup |
| 1.76% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.66% | `python` | `sre_search` | library |
| 1.40% | `python` | `dict_get` | dict |
| 1.35% | `python` | `list_append` | list |
| 1.24% | `python` | `PyUnicode_Format` | str |
| 1.15% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.09% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.08% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.95% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.93% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.92% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.90% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.89% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.88% | `python` | `PyDict_GetItemRef` | dict |
| 0.81% | `python` | `method_vectorcall_FASTCALL` | calls |
| 0.78% | `python` | `_PyJIT_Entry` | compiler |
| 0.75% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.75% | `python` | `PyObject_Str` | dynamic |
| 0.74% | `python` | `_PySuper_Lookup` | dynamic |
| 0.71% | `python` | `insertdict` | dict |
| 0.67% | `python` | `PyUnicode_New` | memory |
| 0.60% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.56% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.54% | `python` | `_PyObject_Realloc` | memory |
| 0.54% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.47% | `python` | `listiter_next` | list |
| 0.45% | `python` | `PyType_IsSubtype` | dynamic |
| 0.44% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.43% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.42% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.40% | `python` | `list_dealloc` | memory |
| 0.40% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.38% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.37% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.37% | `python` | `PyNumber_Remainder` | dynamic |
| 0.36% | `python` | `cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |
| 0.35% | `python` | `builtin_getattr` | lookup |
| 0.35% | `python` | `PyThread_get_thread_ident` | threading |
| 0.33% | `python` | `unicode_dealloc` | memory |
| 0.32% | `python` | `PyUnicode_Concat` | str |
| 0.31% | `python` | `delitem_common` | dynamic |
| 0.28% | `python` | `supercheck` | unknown |
| 0.28% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.27% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.27% | `python` | `_PyDict_Next` | dict |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.49% | `[JIT]` | `jit` | jit |
| 8.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.19% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.62% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.33% | `python` | `_PyCompactLong_Add` | unknown |
| 2.25% | `python` | `PyFloat_FromDouble` | float |
| 2.03% | `python` | `make_range_object` | unknown |
| 1.64% | `python` | `initialize_locals` | interpreter |
| 1.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.46% | `python` | `range_iter` | miscobj |
| 1.33% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.33% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 1.23% | `python` | `_PyObject_Free` | memory |
| 1.22% | `python` | `float_pow` | float |
| 1.20% | `python` | `float_richcompare` | float |
| 1.07% | `python` | `_Py_NewReference` | memory |
| 1.05% | `python` | `_Py_Dealloc` | memory |
| 0.96% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.96% | `python` | `float_compactlong_true_div` | float |
| 0.95% | `python` | `float_dealloc` | memory |
| 0.92% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.92% | `python` | `PyLong_FromLong` | int |
| 0.88% | `python` | `_PyObject_Malloc` | memory |
| 0.88% | `python` | `subtype_dealloc` | memory |
| 0.82% | `python` | `PyType_IsSubtype` | dynamic |
| 0.77% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.74% | `python` | `PyLong_AsLong` | int |
| 0.68% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.67% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.65% | `python` | `PyObject_RichCompare` | dynamic |
| 0.63% | `python` | `py_dealloc` | memory |
| 0.63% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.61% | `python` | `_PyJIT_Entry` | compiler |
| 0.56% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `range_vectorcall` | miscobj |
| 0.49% | `python` | `PyNumber_Index` | dynamic |
| 0.48% | `python` | `PyLong_AsDouble` | int |
| 0.46% | `python` | `PyType_GenericAlloc` | memory |
| 0.44% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.42% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.40% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.38% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.35% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.34% | `python` | `range_dealloc` | memory |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.31% | `python` | `_PyEval_Vector` | interpreter |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `_PyNumber_PowerNoMod` | dynamic |
| 0.29% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `tuple_dealloc` | memory |
| 0.27% | `python` | `PyList_New.constprop.0` | memory |
| 0.26% | `python` | `compactlong_float_subtract` | unknown |
| 0.26% | `python` | `float_compactlong_subtract` | float |
| 0.26% | `python` | `PyObject_GetIter` | dynamic |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.85% | `[JIT]` | `jit` | jit |
| 7.82% | `python` | `_Py_dict_lookup` | lookup |
| 3.76% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 3.41% | `python` | `dict_get` | dict |
| 3.21% | `python` | `_PyObject_Malloc` | memory |
| 2.62% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.42% | `python` | `_PyObject_Free` | memory |
| 2.04% | `python` | `_PyObject_Realloc` | memory |
| 1.69% | `python` | `insertdict` | dict |
| 1.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.55% | `python` | `py_dealloc` | memory |
| 1.43% | `python` | `PyObject_Hash` | dynamic |
| 1.42% | `python` | `_PyDict_Subscript` | dict |
| 1.40% | `python` | `PyFunction_NewWithQualName` | memory |
| 1.37% | `python` | `long_richcompare` | int |
| 1.32% | `python` | `long_hash` | int |
| 1.26% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.19% | `python` | `list_dealloc` | memory |
| 1.09% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 1.07% | `python` | `unsafe_tuple_compare` | unknown |
| 0.95% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.85% | `python` | `list_sort_impl` | list |
| 0.85% | `python` | `func_clear` | unknown |
| 0.84% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.80% | `python` | `gen_dealloc` | memory |
| 0.77% | `python` | `PyObject_RichCompare` | dynamic |
| 0.73% | `python` | `PyDict_GetItemRef` | dict |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.57% | `python` | `_Py_Dealloc` | memory |
| 0.54% | `python` | `make_gen` | miscobj |
| 0.53% | `python` | `tuple_dealloc` | memory |
| 0.53% | `python` | `func_dealloc` | memory |
| 0.52% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.50% | `python` | `PyList_New.constprop.0` | memory |
| 0.48% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.44% | `python` | `tuple_alloc` | memory |
| 0.42% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.42% | `python` | `tuple_subscript` | tuple |
| 0.40% | `python` | `gen_close` | unknown |
| 0.40% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.38% | `python` | `PyObject_GC_Del` | gc |
| 0.37% | `python` | `unsafe_object_compare` | unknown |
| 0.37% | `python` | `find_empty_slot` | dict |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `PyObject_IsTrue` | dynamic |
| 0.33% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.32% | `python` | `gen_finalize` | unknown |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.28% | `python` | `PyObject_Size` | dynamic |
| 0.25% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |

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
| 55.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.98% | `python` | `gen_dealloc` | memory |
| 4.19% | `python` | `make_gen` | miscobj |
| 3.72% | `python` | `_PyObject_Free` | memory |
| 3.39% | `python` | `_PyObject_GC_NewVar` | gc |
| 3.32% | `python` | `_PyObject_Malloc` | memory |
| 2.65% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.47% | `python` | `_PyCompactLong_Subtract` | unknown |
| 2.31% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.92% | `python` | `_PyEval_GetAwaitable` | interpreter |
| 1.90% | `python` | `py_dealloc` | memory |
| 1.83% | `python` | `_Py_MakeCoro` | unknown |
| 1.77% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 1.72% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.71% | `python` | `_PyCompactLong_Add` | unknown |
| 1.22% | `python` | `PyObject_GC_Del` | gc |
| 1.16% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.84% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `python` | `_PyObject_GC_Link` | gc |
| 0.55% | `python` | `gen_finalize` | unknown |
| 0.48% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `PyObject_Malloc` | dynamic |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.01% | `python` | `call_instrumentation_vector.part.0.isra.0` | interpreter |
| 7.54% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 5.45% | `python` | `_Py_call_instrumentation_line` | interpreter |
| 5.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.58% | `python` | `_Py_dict_lookup` | lookup |
| 2.68% | `python` | `_PyObject_Free` | memory |
| 2.60% | `python` | `PyDict_GetItem` | dict |
| 2.47% | `python` | `_PyObject_Malloc` | memory |
| 2.01% | `python` | `set_add_entry_takeref` | miscobj |
| 1.94% | `python` | `siphash13` | str |
| 1.85% | `python` | `PyLong_FromLong` | int |
| 1.69% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.61% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 1.21% | `python` | `PySet_Add` | miscobj |
| 1.19% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 1.13% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.07% | `python` | `unicode_decode_utf8.part.0` | str |
| 1.07% | `python` | `intern_common` | str |
| 1.04% | `python` | `find_first_nonascii` | str |
| 0.97% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.95% | `tracer.cpython-316-x86_64-linux-gnu.so` | `CTracer_set_pdata_stack.constprop.0` | library |
| 0.88% | `python` | `PyUnicode_New.part.0` | memory |
| 0.84% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.83% | `python` | `PyObject_SetAttr` | dynamic |
| 0.80% | `python` | `sys_trace_start` | library |
| 0.76% | `python` | `PyEval_GetFrame` | interpreter |
| 0.74% | `python` | `frame_dealloc` | memory |
| 0.74% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.73% | `python` | `_PyType_GetDict` | dynamic |
| 0.72% | `python` | `_PyDict_LoadGlobalStackRef` | dict |
| 0.71% | `python` | `sys_trace_return` | library |
| 0.69% | `python` | `_Py_call_instrumentation_arg` | unknown |
| 0.69% | `python` | `PyObject_GC_Del` | gc |
| 0.66% | `python` | `PyObject_Hash` | dynamic |
| 0.65% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.64% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.63% | `python` | `py_dealloc` | memory |
| 0.60% | `python` | `_PyFrame_MakeAndSetFrameObject` | interpreter |
| 0.57% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.56% | `python` | `long_hash` | int |
| 0.55% | `python` | `PyFrame_GetCode` | exceptions |
| 0.55% | `python` | `_PyUnicode_InternMortal` | str |
| 0.54% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.54% | `python` | `_PyCode_GetCode` | interpreter |
| 0.54% | `python` | `PyObject_SetAttrString` | dynamic |
| 0.54% | `python` | `_Py_call_instrumentation` | unknown |
| 0.53% | `python` | `PyUnicode_InternFromString` | str |
| 0.50% | `python` | `_PyCompactLong_Add` | unknown |
| 0.47% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.46% | `python` | `unicode_dealloc` | memory |
| 0.45% | `python` | `getset_set` | unknown |
| 0.44% | `python` | `PyFrame_GetLineNumber` | exceptions |
| 0.40% | `python` | `hashtable_unicode_hash` | unknown |
| 0.40% | `python` | `frame_trace_set` | unknown |
| 0.36% | `python` | `_Py_Dealloc` | memory |
| 0.36% | `python` | `_PyEval_LoadGlobalStackRef` | interpreter |
| 0.32% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.28% | `python` | `_PyFrame_New_NoTrack` | interpreter |
| 0.26% | `python` | `PyFrame_GetLasti` | exceptions |
| 0.26% | `python` | `Py_HashBuffer` | unknown |
| 0.25% | `python` | `_PyErr_SetRaisedException` | exceptions |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.14% | `[JIT]` | `jit` | jit |
| 7.36% | `python` | `long_bitwise` | int |
| 7.30% | `python` | `_PyObject_Free` | memory |
| 5.12% | `python` | `_PyObject_Malloc` | memory |
| 3.84% | `python` | `long_rshift1` | int |
| 3.75% | `python` | `l_mod` | int |
| 3.33% | `python` | `long_alloc` | memory |
| 1.94% | `python` | `maybe_small_long` | unknown |
| 1.91% | `python` | `long_rshift` | int |
| 1.78% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.65% | `python` | `PyNumber_Xor` | dynamic |
| 1.57% | `python` | `long_dealloc` | memory |
| 1.43% | `python` | `PyLong_FromLong` | int |
| 1.42% | `python` | `PyNumber_Rshift` | dynamic |
| 1.26% | `python` | `PyLong_FromSsize_t` | int |
| 1.19% | `python` | `_PyCompactLong_Add` | unknown |
| 1.18% | `python` | `_Py_Dealloc` | memory |
| 1.16% | `python` | `compactlongs_guard` | unknown |
| 1.14% | `python` | `PyNumber_Remainder` | dynamic |
| 1.00% | `python` | `long_mod` | int |
| 0.97% | `python` | `_Py_NewReference` | memory |
| 0.93% | `python` | `make_range_object` | unknown |
| 0.89% | `python` | `_PyLong_FromMedium` | int |
| 0.87% | `python` | `long_xor` | int |
| 0.66% | `python` | `compactlongs_and` | unknown |
| 0.64% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.64% | `python` | `range_iter` | miscobj |
| 0.44% | `python` | `list_dealloc` | memory |
| 0.43% | `python` | `set_lookkey` | miscobj |
| 0.43% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.41% | `python` | `PyNumber_And` | dynamic |
| 0.39% | `python` | `PyObject_Malloc` | dynamic |
| 0.38% | `python` | `PyObject_Free` | dynamic |
| 0.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.30% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.30% | `python` | `PyList_New.constprop.0` | memory |
| 0.30% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.27% | `python` | `zip_next` | unknown |
| 0.26% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.26% | `python` | `PyLong_AsLong` | int |
| 0.25% | `python` | `PyNumber_Index` | dynamic |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.05% | `[JIT]` | `jit` | jit |
| 7.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.13% | `python` | `_Py_dict_lookup` | lookup |
| 4.07% | `python` | `_PyObject_Malloc` | memory |
| 3.53% | `python` | `_PyObject_Free` | memory |
| 2.94% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.02% | `python` | `set_lookkey` | miscobj |
| 1.86% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.33% | `python` | `initialize_locals` | interpreter |
| 1.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.26% | `python` | `py_dealloc` | memory |
| 1.23% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.15% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.12% | `python` | `insertdict` | dict |
| 1.09% | `python` | `long_richcompare` | int |
| 0.99% | `python` | `PyLong_FromVoidPtr` | int |
| 0.99% | `python` | `PyObject_Hash` | dynamic |
| 0.95% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.90% | `python` | `_Py_Dealloc` | memory |
| 0.88% | `python` | `_PyObject_Realloc` | memory |
| 0.88% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.87% | `python` | `_PySet_Contains` | miscobj |
| 0.83% | `python` | `sys_audit_tstate` | unknown |
| 0.81% | `python` | `dictiter_iternextitem` | dict |
| 0.75% | `python` | `insert_to_emptydict` | dict |
| 0.74% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.71% | `python` | `_PyDict_Subscript` | dict |
| 0.71% | `python` | `long_hash` | int |
| 0.63% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.62% | `python` | `PySys_Audit` | unknown |
| 0.60% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `tuple_dealloc` | memory |
| 0.56% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.56% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.56% | `python` | `dict_get` | dict |
| 0.56% | `python` | `builtin_id` | unknown |
| 0.55% | `python` | `list_append` | list |
| 0.53% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.48% | `python` | `_Py_NewReference` | memory |
| 0.47% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.47% | `python` | `tuple_alloc` | memory |
| 0.46% | `python` | `_PyObject_Calloc` | memory |
| 0.45% | `python` | `PyCMethod_New` | memory |
| 0.45% | `python` | `PyDict_Contains` | dict |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.41% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.41% | `python` | `list_dealloc` | memory |
| 0.41% | `python` | `object___reduce_ex__` | dynamic |
| 0.39% | `python` | `_PyDict_Next` | dict |
| 0.38% | `python` | `PyDict_GetItemRef` | dict |
| 0.38% | `python` | `_PyObject_GC_New` | gc |
| 0.36% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.33% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.32% | `python` | `dict_dealloc` | memory |
| 0.31% | `python` | `new_dict.constprop.0` | dict |
| 0.28% | `python` | `PyList_New` | memory |
| 0.28% | `python` | `dict_merge` | dict |
| 0.26% | `python` | `PyMethod_New` | memory |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `method_get` | dynamic |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.66% | `[JIT]` | `jit` | jit |
| 10.87% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.30% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.48% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 2.39% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.03% | `python` | `listiter_next` | list |
| 1.76% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.58% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.32% | `python` | `_PyObject_Malloc` | memory |
| 1.30% | `python` | `gc_collect_main` | gc |
| 1.22% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.11% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.81% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.78% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.66% | `python` | `_PyJIT_Entry` | compiler |
| 0.65% | `python` | `_PyObject_Free` | memory |
| 0.61% | `python` | `_Py_type_getattro` | lookup |
| 0.58% | `python` | `_PyType_GetDict` | dynamic |
| 0.56% | `python` | `py_dealloc` | memory |
| 0.48% | `python` | `visit_decref` | gc |
| 0.46% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.44% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.43% | `python` | `PyMethod_New` | memory |
| 0.42% | `python` | `PyType_IsSubtype` | dynamic |
| 0.40% | `python` | `subtype_dealloc` | memory |
| 0.37% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.35% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.34% | `python` | `list_iter` | list |
| 0.34% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.33% | `python` | `_Py_Dealloc` | memory |
| 0.33% | `python` | `PyDict_GetItemRef` | dict |
| 0.31% | `python` | `PyObject_RichCompare` | dynamic |
| 0.30% | `python` | `_PyCompactLong_Add` | unknown |
| 0.30% | `python` | `long_to_decimal_string_internal` | int |
| 0.27% | `python` | `method_dealloc` | memory |
| 0.27% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.25% | `python` | `initialize_locals` | interpreter |

## django_template

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.28% | `[JIT]` | `jit` | jit |
| 9.40% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.72% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.41% | `python` | `_PyObject_Malloc` | memory |
| 2.38% | `python` | `_PyObject_Free` | memory |
| 2.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.06% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.02% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.92% | `python` | `initialize_locals` | interpreter |
| 1.66% | `python` | `replace` | str |
| 1.46% | `python` | `py_dealloc` | memory |
| 1.39% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.32% | `python` | `_Py_dict_lookup` | lookup |
| 1.22% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.19% | `python` | `PyType_IsSubtype` | dynamic |
| 1.15% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.07% | `python` | `unicode_replace` | str |
| 1.04% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.96% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.90% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.88% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.81% | `python` | `long_to_decimal_string_internal` | int |
| 0.77% | `python` | `insertdict` | dict |
| 0.76% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.70% | `python` | `_PyEvalFramePushAndInit_Ex` | interpreter |
| 0.65% | `python` | `tuple_alloc` | memory |
| 0.61% | `python` | `object_isinstance` | dynamic |
| 0.60% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.60% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.56% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.54% | `python` | `tuple_dealloc` | memory |
| 0.52% | `python` | `_PyObject_GC_New` | gc |
| 0.51% | `python` | `listiter_next` | list |
| 0.50% | `python` | `PyMethod_New` | memory |
| 0.50% | `python` | `PyDict_GetItemRef` | dict |
| 0.47% | `python` | `tuple_iter` | tuple |
| 0.47% | `python` | `_PyJIT_Entry` | compiler |
| 0.46% | `python` | `dict_dealloc` | memory |
| 0.45% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.45% | `python` | `PyObject_IsInstance` | dynamic |
| 0.44% | `python` | `enum_next` | miscobj |
| 0.43% | `python` | `_PyType_GetDict` | dynamic |
| 0.40% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.39% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.38% | `python` | `PyType_GenericAlloc` | memory |
| 0.37% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.34% | `python` | `PyThread_get_thread_ident` | threading |
| 0.34% | `python` | `unicode_new` | memory |
| 0.33% | `python` | `getset_get` | dynamic |
| 0.33% | `python` | `func_clear` | unknown |
| 0.32% | `python` | `PyObject_GetIter` | dynamic |
| 0.32% | `python` | `list_extend_lock_held` | list |
| 0.32% | `python` | `chain_next` | unknown |
| 0.31% | `python` | `gen_dealloc` | memory |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `python` | `new_dict.constprop.0` | dict |
| 0.29% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.29% | `python` | `_PyObject_Calloc` | memory |
| 0.29% | `python` | `chain_new` | memory |
| 0.28% | `python` | `PyDict_New` | memory |
| 0.28% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.27% | `python` | `PyObject_Str` | dynamic |
| 0.27% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.27% | `python` | `PyObject_GC_Del` | gc |
| 0.26% | `python` | `dict_merge` | dict |
| 0.26% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.25% | `python` | `PySequence_Contains` | dynamic |
| 0.25% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.25% | `python` | `list_subscript` | list |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.60% | `[JIT]` | `jit` | jit |
| 9.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.47% | `python` | `sre_ucs1_match` | library |
| 3.67% | `python` | `gc_collect_main` | gc |
| 3.52% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.58% | `python` | `_PyObject_Malloc` | memory |
| 2.48% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.98% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.76% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `_PyObject_Free` | memory |
| 1.37% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.31% | `python` | `list_dealloc` | memory |
| 1.26% | `python` | `visit_decref` | gc |
| 1.22% | `python` | `_Py_dict_lookup` | lookup |
| 1.11% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.07% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.85% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.80% | `python` | `py_dealloc` | memory |
| 0.76% | `python` | `visit_reachable` | gc |
| 0.75% | `python` | `PyType_IsSubtype` | dynamic |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `_Py_Dealloc` | memory |
| 0.54% | `python` | `list_slice_lock_held` | list |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.52% | `python` | `_PyJIT_Entry` | compiler |
| 0.52% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.49% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.48% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.47% | `python` | `PyUnicode_Format` | str |
| 0.47% | `python` | `sre_ucs1_count` | library |
| 0.46% | `python` | `list_extend_lock_held` | list |
| 0.44% | `python` | `tuple_dealloc` | memory |
| 0.41% | `python` | `PyObject_SetAttr` | dynamic |
| 0.40% | `python` | `sre_search` | library |
| 0.37% | `python` | `tuple_alloc` | memory |
| 0.36% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.36% | `python` | `insertdict` | dict |
| 0.36% | `python` | `PyDict_GetItemRef` | dict |
| 0.36% | `libc.so.6` | `_int_malloc` | libc |
| 0.35% | `python` | `split` | str |
| 0.35% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.34% | `python` | `_PyDict_Subscript` | dict |
| 0.34% | `python` | `_PyObject_Realloc` | memory |
| 0.34% | `python` | `PyList_New.constprop.0` | memory |
| 0.32% | `python` | `list_traverse` | gc |
| 0.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.31% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.30% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.30% | `python` | `_PyType_GetDict` | dynamic |
| 0.30% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.28% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.28% | `python` | `dict_traverse` | gc |
| 0.26% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.26% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.11% | `[JIT]` | `jit` | jit |
| 2.73% | `python` | `_PyObject_Malloc` | memory |
| 1.94% | `libz.so.1.3` | `inflate` | library |
| 1.86% | `python` | `_PyObject_Free` | memory |
| 1.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.97% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.91% | `python` | `_Py_Dealloc` | memory |
| 0.84% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.83% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `libz.so.1.3` | `0x000000000000381f` | library |
| 0.70% | `python` | `py_dealloc` | memory |
| 0.57% | `libc.so.6` | `_int_malloc` | libc |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.54% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.53% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.52% | `python` | `PyLong_FromString` | int |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `PyObject_RichCompare` | dynamic |
| 0.42% | `python` | `tuple_dealloc` | memory |
| 0.42% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 0.40% | `python` | `_Py_dict_lookup` | lookup |
| 0.39% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.39% | `libz.so.1.3` | `0x00000000000025b7` | library |
| 0.38% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.37% | `python` | `_PyJIT_Entry` | compiler |
| 0.36% | `python` | `bytes_subscript` | str |
| 0.36% | `python` | `PySlice_New` | memory |
| 0.36% | `python` | `clear_slots` | unknown |
| 0.35% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.34% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.34% | `python` | `PyObject_IsTrue` | dynamic |
| 0.33% | `python` | `list_dealloc` | memory |
| 0.33% | `python` | `PyList_New.constprop.0` | memory |
| 0.33% | `python` | `_io_open` | unknown |
| 0.32% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.32% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.32% | `libz.so.1.3` | `adler32_z` | library |
| 0.31% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.31% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.31% | `python` | `subtype_dealloc` | memory |
| 0.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.31% | `python` | `do_mkvalue` | unknown |
| 0.31% | `python` | `PyUnicode_Decode` | str |
| 0.30% | `binascii.cpython-316-x86_64-linux-gnu.so` | `binascii_a2b_hex_impl.isra.0` | library |
| 0.30% | `python` | `unicode_from_format` | str |
| 0.30% | `python` | `_PyCompactLong_Add` | unknown |
| 0.29% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.29% | `python` | `PyObject_GetItem` | dynamic |
| 0.29% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.29% | `python` | `siphash13` | str |
| 0.29% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.28% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.28% | `python` | `bytes_richcompare` | str |
| 0.28% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.28% | `python` | `convertitem.constprop.0` | unknown |
| 0.28% | `python` | `PyLong_FromSsize_t` | int |
| 0.27% | `python` | `PyBytesWriter_Create` | unknown |
| 0.26% | `python` | `PyObject_Size` | dynamic |
| 0.25% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.25% | `python` | `_PyObject_CallFunctionVa` | dynamic |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.75% | `[JIT]` | `jit` | jit |
| 12.06% | `python` | `PySlice_AdjustIndices` | miscobj |
| 5.83% | `python` | `list_ass_slice_lock_held` | list |
| 5.00% | `python` | `list_slice_wrap` | list |
| 4.85% | `python` | `py_dealloc` | memory |
| 3.46% | `python` | `_PyObject_Free` | memory |
| 3.24% | `python` | `PySlice_New` | memory |
| 3.20% | `python` | `PySlice_Unpack` | miscobj |
| 2.89% | `python` | `_PyEval_SliceIndex` | interpreter |
| 2.77% | `python` | `list_dealloc` | memory |
| 2.73% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 2.56% | `python` | `list_ass_subscript` | list |
| 2.52% | `python` | `_PyObject_Malloc` | memory |
| 2.48% | `python` | `_PyCompactLong_Add` | unknown |
| 2.46% | `python` | `PyObject_GC_UnTrack` | gc |
| 2.15% | `python` | `slice_dealloc` | memory |
| 1.88% | `python` | `PyList_New.constprop.0` | memory |
| 1.58% | `python` | `PySequence_Fast` | dynamic |
| 1.46% | `python` | `_PyList_SliceSubscript` | list |
| 1.40% | `python` | `_Py_Dealloc` | memory |
| 1.39% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.39% | `python` | `list_insert` | list |
| 1.02% | `python` | `PyObject_SetItem` | dynamic |
| 0.91% | `python` | `_Py_NewReference` | memory |
| 0.90% | `python` | `list_pop` | list |
| 0.85% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.80% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.70% | `python` | `_PyNumber_Index` | dynamic |
| 0.52% | `python` | `list_slice_lock_held` | list |
| 0.50% | `python` | `PyLong_AsSsize_t` | int |

## fastapi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.91% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 14.34% | `[JIT]` | `jit` | jit |
| 3.03% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.97% | `python` | `_PyObject_Malloc` | memory |
| 1.62% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.46% | `python` | `initialize_locals` | interpreter |
| 1.33% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.29% | `python` | `_PyObject_Free` | memory |
| 1.06% | `python` | `PyObject_RichCompare` | dynamic |
| 0.95% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.93% | `libc.so.6` | `pthread_rwlock_unlock@@GLIBC_2.34` | libc |
| 0.84% | `libc.so.6` | `pthread_rwlock_rdlock@GLIBC_2.2.5` | libc |
| 0.76% | `python` | `_PyEval_Vector` | interpreter |
| 0.69% | `python` | `bytes_richcompare` | str |
| 0.67% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.65% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.62% | `python` | `_Py_dict_lookup` | lookup |
| 0.61% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.61% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.58% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.56% | `python` | `py_dealloc` | memory |
| 0.54% | `python` | `slot_tp_richcompare` | dynamic |
| 0.53% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.53% | `python` | `tuple_dealloc` | memory |
| 0.51% | `python` | `_Py_Dealloc` | memory |
| 0.46% | `python` | `gc_collect_main` | gc |
| 0.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.37% | `python` | `tuple_alloc` | memory |
| 0.35% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.35% | `python` | `set_lookkey` | miscobj |
| 0.34% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.32% | `libc.so.6` | `malloc` | libc |
| 0.32% | `python` | `visit_decref` | gc |
| 0.31% | `python` | `visit_reachable` | gc |
| 0.29% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.29% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.28% | `python` | `long_richcompare` | int |
| 0.28% | `python` | `PyDict_GetItemRef` | dict |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.28% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.27% | `python` | `sre_ucs1_match` | library |
| 0.27% | `python` | `PyObject_IsInstance` | dynamic |
| 0.27% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.27% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `libc.so.6` | `_int_malloc` | libc |
| 0.25% | `python` | `lookup_method_ex.constprop.0` | unknown |

## float

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.15% | `[JIT]` | `jit` | jit |
| 5.59% | `python` | `subtype_traverse` | gc |
| 4.17% | `libm.so.6` | `__sin_fma` | library |
| 3.75% | `python` | `PyFloat_FromDouble` | float |
| 3.71% | `libm.so.6` | `__cos_fma` | library |
| 3.18% | `python` | `_PyObject_Malloc` | memory |
| 3.16% | `python` | `visit_decref` | gc |
| 2.87% | `python` | `visit_reachable` | gc |
| 2.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.76% | `python` | `_PyObject_Free` | memory |
| 2.33% | `python` | `gc_collect_main` | gc |
| 1.87% | `python` | `clear_slots` | unknown |
| 1.82% | `python` | `_Py_Dealloc` | memory |
| 1.52% | `python` | `_Py_NewReference` | memory |
| 1.48% | `python` | `PyFloat_AsDouble` | float |
| 1.44% | `python` | `float_dealloc` | memory |
| 1.38% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.33% | `python` | `_PyMember_GetOffset` | unknown |
| 1.31% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.21% | `python` | `list_dealloc` | memory |
| 1.13% | `python` | `initialize_locals` | interpreter |
| 1.01% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.00% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.99% | `python` | `long_float` | int |
| 0.92% | `python` | `list_slice_lock_held` | list |
| 0.85% | `python` | `subtype_dealloc` | memory |
| 0.77% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.76% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.63% | `python` | `PyType_IsSubtype` | dynamic |
| 0.54% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sin` | library |
| 0.50% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.49% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.48% | `python` | `float_compactlong_true_div` | float |
| 0.47% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.47% | `python` | `PyType_GenericAlloc` | memory |
| 0.45% | `python` | `list_traverse` | gc |
| 0.43% | `python` | `py_dealloc` | memory |
| 0.42% | `python` | `_PyLong_FromMedium` | int |
| 0.37% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.30% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.28% | `python` | `PyObject_GC_Del` | gc |
| 0.28% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.26% | `python` | `long_dealloc` | memory |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.53% | `python` | `visit_reachable` | gc |
| 22.87% | `python` | `visit_decref` | gc |
| 17.10% | `python` | `gc_collect_main` | gc |
| 10.03% | `python` | `dict_traverse` | gc |
| 3.55% | `python` | `func_traverse` | gc |
| 3.43% | `[JIT]` | `jit` | jit |
| 2.10% | `python` | `subtype_traverse` | gc |
| 1.93% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.43% | `python` | `tuple_traverse` | gc |
| 1.30% | `python` | `set_traverse` | gc |
| 1.27% | `python` | `type_traverse` | gc |
| 1.12% | `python` | `type_is_gc` | gc |
| 0.98% | `python` | `list_traverse` | gc |
| 0.62% | `python` | `meth_traverse` | gc |
| 0.59% | `python` | `_PyObject_Malloc` | memory |
| 0.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.46% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.39% | `python` | `gc_traverse` | gc |
| 0.37% | `python` | `_PyTuple_MaybeUntrack` | gc |
| 0.37% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.31% | `python` | `subtype_dealloc` | memory |
| 0.31% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.28% | `python` | `initialize_locals` | interpreter |
| 0.28% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `_PyObject_Free` | memory |
| 0.26% | `python` | `PyObject_IS_GC` | gc |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.14% | `python` | `visit_reachable` | gc |
| 27.38% | `python` | `visit_decref` | gc |
| 14.29% | `python` | `list_traverse` | gc |
| 6.53% | `python` | `gc_collect_main` | gc |
| 4.48% | `python` | `dict_traverse` | gc |
| 1.57% | `[JIT]` | `jit` | jit |
| 1.46% | `python` | `func_traverse` | gc |
| 0.71% | `python` | `type_traverse` | gc |
| 0.57% | `python` | `subtype_traverse` | gc |
| 0.55% | `python` | `set_traverse` | gc |
| 0.54% | `python` | `tuple_traverse` | gc |
| 0.52% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.43% | `python` | `type_is_gc` | gc |
| 0.29% | `python` | `PyLong_FromLong` | int |
| 0.27% | `python` | `list_dealloc` | memory |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.68% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.49% | `[JIT]` | `jit` | jit |
| 1.93% | `python` | `gc_collect_main` | gc |
| 1.89% | `python` | `_PyObject_Malloc` | memory |
| 1.73% | `python` | `_PyObject_Free` | memory |
| 1.69% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.65% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.48% | `python` | `gen_dealloc` | memory |
| 1.36% | `python` | `initialize_locals` | interpreter |
| 1.28% | `python` | `make_range_object` | unknown |
| 1.26% | `python` | `_PyEval_Vector` | interpreter |
| 1.22% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.16% | `python` | `visit_reachable` | gc |
| 1.09% | `python` | `visit_decref` | gc |
| 1.00% | `python` | `make_gen` | miscobj |
| 0.95% | `python` | `range_subscript` | miscobj |
| 0.93% | `python` | `py_dealloc` | memory |
| 0.92% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.88% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.83% | `python` | `_PyLong_FromMedium` | int |
| 0.82% | `python` | `slot_tp_iter` | unknown |
| 0.81% | `python` | `PyNumber_Add` | dynamic |
| 0.78% | `python` | `long_add_method` | int |
| 0.78% | `python` | `PySlice_New` | memory |
| 0.77% | `python` | `subtype_traverse` | gc |
| 0.77% | `python` | `_Py_Dealloc` | memory |
| 0.76% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.71% | `python` | `_PySlice_GetLongIndices` | miscobj |
| 0.69% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `long_richcompare` | int |
| 0.66% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.60% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.57% | `python` | `_PyEval_GetIter` | interpreter |
| 0.54% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.52% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.50% | `python` | `_PyJIT_Entry` | compiler |
| 0.50% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.48% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.48% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.46% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.44% | `python` | `range_dealloc` | memory |
| 0.43% | `python` | `long_dealloc` | memory |
| 0.38% | `python` | `PyObject_GetIter` | dynamic |
| 0.38% | `python` | `long_mul` | int |
| 0.38% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.37% | `python` | `_Py_NewReference` | memory |
| 0.35% | `python` | `PyObject_GC_Del` | gc |
| 0.35% | `python` | `PyObject_GetItem` | dynamic |
| 0.34% | `python` | `long_div` | int |
| 0.32% | `python` | `PyNumber_Multiply` | dynamic |
| 0.32% | `python` | `PyLong_FromLong` | int |
| 0.28% | `python` | `subtype_dealloc` | memory |
| 0.28% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.27% | `python` | `PyNumber_Index` | dynamic |

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
| 54.27% | `[JIT]` | `jit` | jit |
| 15.96% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.33% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.66% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.72% | `python` | `initialize_locals` | interpreter |
| 1.40% | `python` | `long_bitwise` | int |
| 1.13% | `python` | `_PyObject_Free` | memory |
| 1.11% | `python` | `insertdict` | dict |
| 1.06% | `python` | `_PyObject_Malloc` | memory |
| 1.01% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.98% | `python` | `_PyCompactLong_Add` | unknown |
| 0.89% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.69% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.63% | `python` | `set_lookkey` | miscobj |
| 0.62% | `python` | `PyNumber_InPlaceXor` | dynamic |
| 0.61% | `python` | `_PyJIT_Entry` | compiler |
| 0.41% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.39% | `python` | `_Py_dict_lookup` | lookup |
| 0.38% | `python` | `_Py_Dealloc` | memory |
| 0.34% | `python` | `long_alloc` | memory |
| 0.33% | `python` | `PyFloat_FromDouble` | float |
| 0.33% | `python` | `set_add_entry_takeref` | miscobj |
| 0.32% | `python` | `long_dealloc` | memory |
| 0.32% | `python` | `PyDict_SetItem` | dict |
| 0.27% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.25% | `python` | `_Py_NewReference` | memory |

## hexiom

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.55% | `[JIT]` | `jit` | jit |
| 13.64% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.99% | `python` | `PyObject_RichCompareBool` | dynamic |
| 3.74% | `python` | `list_contains` | list |
| 2.95% | `python` | `long_richcompare` | int |
| 2.76% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.20% | `python` | `gen_iternext` | miscobj |
| 1.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.22% | `python` | `_PyJIT_Entry` | compiler |
| 1.10% | `python` | `PyObject_Size` | dynamic |
| 1.10% | `python` | `PyLong_FromLong` | int |
| 1.07% | `python` | `PyLong_FromSsize_t` | int |
| 1.07% | `python` | `_PyObject_Malloc` | memory |
| 1.05% | `python` | `builtin_sum` | unknown |
| 0.90% | `python` | `_PyObject_Free` | memory |
| 0.86% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.65% | `python` | `make_range_object` | unknown |
| 0.62% | `python` | `PyIter_Next` | dynamic |
| 0.50% | `python` | `PySequence_Contains` | dynamic |
| 0.46% | `python` | `range_iter` | miscobj |
| 0.42% | `python` | `py_dealloc` | memory |
| 0.42% | `python` | `_PyCompactLong_Add` | unknown |
| 0.38% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `_Py_Dealloc` | memory |
| 0.34% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.29% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.29% | `python` | `PyList_New.constprop.0` | memory |
| 0.27% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.25% | `python` | `unicodekeys_lookup_unicode` | lookup |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.85% | `[JIT]` | `jit` | jit |
| 12.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.74% | `python` | `sre_search` | library |
| 2.03% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `python` | `gc_collect_main` | gc |
| 1.79% | `python` | `_Py_dict_lookup` | lookup |
| 1.70% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.12% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.05% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.04% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.98% | `python` | `_PyObject_Free` | memory |
| 0.91% | `python` | `sre_ucs1_count` | library |
| 0.85% | `python` | `_PyDict_SubscriptKnownHash` | dict |
| 0.81% | `python` | `set_lookkey` | miscobj |
| 0.74% | `python` | `initialize_locals` | interpreter |
| 0.73% | `python` | `PyObject_IsTrue` | dynamic |
| 0.66% | `python` | `_Py_Dealloc` | memory |
| 0.64% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.63% | `python` | `py_dealloc` | memory |
| 0.63% | `python` | `_PyJIT_Entry` | compiler |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.59% | `python` | `visit_decref` | gc |
| 0.58% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `sre_ucs1_match` | library |
| 0.54% | `python` | `_PyUnicode_Equal` | str |
| 0.53% | `python` | `PyObject_GetItem` | dynamic |
| 0.52% | `python` | `insertdict` | dict |
| 0.52% | `python` | `_PyDict_Subscript` | dict |
| 0.52% | `libc.so.6` | `__strcmp_avx2` | libc |
| 0.50% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.50% | `libc.so.6` | `_int_malloc` | libc |
| 0.46% | `python` | `list_contains` | list |
| 0.42% | `python` | `PyUnicode_Concat` | str |
| 0.42% | `python` | `insert_to_emptydict` | dict |
| 0.41% | `python` | `_PyDict_FromItems` | dict |
| 0.40% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `python` | `_PyUnicode_TranslateCharmap` | str |
| 0.38% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.37% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.37% | `python` | `visit_reachable` | gc |
| 0.37% | `python` | `PyObject_RichCompare` | dynamic |
| 0.37% | `python` | `_PyCompactLong_Add` | unknown |
| 0.36% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.35% | `python` | `list_subscript` | list |
| 0.34% | `python` | `PyObject_Hash` | dynamic |
| 0.33% | `python` | `PyList_New.constprop.0` | memory |
| 0.30% | `python` | `pattern_new_match` | memory |
| 0.30% | `python` | `list_dealloc` | memory |
| 0.30% | `python` | `PyType_IsSubtype` | dynamic |
| 0.29% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.29% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.28% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.27% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.26% | `python` | `dict_dealloc` | memory |
| 0.26% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.26% | `python` | `tuple_richcompare` | tuple |
| 0.26% | `python` | `PyDict_GetItemRef` | dict |
| 0.26% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.25% | `python` | `object_richcompare` | dynamic |
| 0.25% | `python` | `_Py_BuildMap_StackRefSteal` | unknown |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.41% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 6.67% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.18% | `python` | `_PyObject_Malloc` | memory |
| 6.07% | `python` | `_PyObject_Free` | memory |
| 5.41% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 5.29% | `python` | `siphash13` | str |
| 3.90% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.03% | `[JIT]` | `jit` | jit |
| 2.88% | `python` | `PyUnicode_Substring` | str |
| 2.83% | `python` | `_Py_dict_lookup` | lookup |
| 2.70% | `python` | `insertdict` | dict |
| 2.65% | `python` | `PyLong_FromString` | int |
| 2.39% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 2.09% | `python` | `PyUnicode_New.part.0` | memory |
| 1.93% | `python` | `find_empty_slot` | dict |
| 1.49% | `python` | `build_indices_unicode` | dict |
| 1.30% | `libc.so.6` | `_int_malloc` | libc |
| 1.29% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.25% | `python` | `unicode_dealloc` | memory |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.98% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.89% | `python` | `_Py_Dealloc` | memory |
| 0.75% | `python` | `unicode_hash` | str |
| 0.69% | `python` | `sre_ucs1_match` | library |
| 0.68% | `python` | `insert_to_emptydict` | dict |
| 0.64% | `python` | `pattern_new_match` | memory |
| 0.61% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.60% | `python` | `new_keys_object` | dict |
| 0.59% | `python` | `dictresize` | dict |
| 0.59% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.54% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.51% | `python` | `_Py_NewReference` | memory |
| 0.49% | `python` | `PyDict_GetItemRef` | dict |
| 0.49% | `python` | `py_dealloc` | memory |
| 0.44% | `python` | `maybe_small_long` | unknown |
| 0.44% | `python` | `_PyObject_Realloc` | memory |
| 0.40% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.40% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.39% | `python` | `Py_HashBuffer` | unknown |
| 0.38% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 0.38% | `python` | `PyObject_Hash` | dynamic |
| 0.37% | `python` | `PyDict_New` | memory |
| 0.36% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.34% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.34% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.33% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.32% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.32% | `libc.so.6` | `malloc` | libc |
| 0.30% | `python` | `allocate_from_new_pool` | memory |
| 0.28% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.28% | `python` | `long_alloc` | memory |
| 0.25% | `python` | `PyObject_Malloc` | dynamic |
| 0.25% | `libc.so.6` | `_int_free` | libc |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.18% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 5.90% | `[JIT]` | `jit` | jit |
| 5.09% | `python` | `PyUnicodeWriter_WriteChar` | str |
| 4.28% | `python` | `_PyUnicode_ResizeCompact` | str |
| 3.95% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_size` | library |
| 3.76% | `python` | `_PyObject_Malloc` | memory |
| 3.44% | `python` | `_Py_dict_lookup` | lookup |
| 3.11% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 3.02% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 2.95% | `_json.cpython-316-x86_64-linux-gnu.so` | `write_escaped_ascii` | library |
| 2.80% | `python` | `PyDict_Next` | dict |
| 2.74% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 2.62% | `python` | `PyUnicodeWriter_WriteASCII` | str |
| 2.25% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.11% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 2.08% | `python` | `convertitem.constprop.0` | unknown |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.96% | `python` | `_PyObject_Free` | memory |
| 1.80% | `python` | `_PyObject_Realloc` | memory |
| 1.70% | `python` | `initialize_locals` | interpreter |
| 1.61% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.49% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.49% | `python` | `PyDict_GetItemRef` | dict |
| 1.46% | `python` | `long_to_decimal_string_internal` | int |
| 1.43% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 1.40% | `python` | `PyUnicodeWriter_WriteStr` | str |
| 1.02% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.97% | `python` | `py_dealloc` | memory |
| 0.91% | `python` | `tuple_dealloc` | memory |
| 0.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.80% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_write_string` | library |
| 0.75% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.70% | `python` | `tuple_alloc` | memory |
| 0.66% | `python` | `PyType_IsSubtype` | dynamic |
| 0.63% | `python` | `delitem_common` | dynamic |
| 0.57% | `python` | `_Py_Dealloc` | memory |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.55% | `python` | `long_hash` | int |
| 0.55% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.53% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `memcpy@plt` | memory |
| 0.48% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.45% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.43% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.43% | `python` | `insertdict` | dict |
| 0.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.40% | `python` | `PyDict_DelItem` | dict |
| 0.40% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicodeWriter_WriteChar@plt` | library |
| 0.38% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.37% | `python` | `new_dict.constprop.0` | dict |
| 0.36% | `python` | `PyLong_FromVoidPtr` | int |
| 0.36% | `python` | `dict_dealloc` | memory |
| 0.35% | `_json.cpython-316-x86_64-linux-gnu.so` | `ascii_escape_unicode_and_size` | library |
| 0.34% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_new` | library |
| 0.34% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.33% | `python` | `object_isinstance` | dynamic |
| 0.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.29% | `python` | `PyDict_Contains` | dict |
| 0.29% | `python` | `PyArg_ParseTupleAndKeywords` | calls |
| 0.29% | `python` | `object_recursive_isinstance` | dynamic |
| 0.28% | `python` | `PyObject_IsTrue` | dynamic |
| 0.28% | `python` | `PyUnicodeWriter_Create` | str |
| 0.28% | `python` | `PyObject_Hash` | dynamic |
| 0.27% | `python` | `_Py_NewReference` | memory |
| 0.27% | `python` | `PyDict_SetItem` | dict |
| 0.26% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.26% | `_json.cpython-316-x86_64-linux-gnu.so` | `encoder_dealloc` | library |
| 0.26% | `python` | `PyObject_IsInstance` | dynamic |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.80% | `_json.cpython-316-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 8.14% | `_json.cpython-316-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 7.86% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 6.73% | `python` | `siphash13` | str |
| 6.68% | `python` | `_PyObject_Malloc` | memory |
| 5.87% | `python` | `_PyObject_Free` | memory |
| 4.05% | `python` | `PyUnicode_Substring` | str |
| 3.45% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 3.39% | `python` | `PyLong_FromString` | int |
| 3.29% | `python` | `_Py_dict_lookup` | lookup |
| 3.08% | `python` | `PyUnicode_New.part.0` | memory |
| 3.07% | `python` | `insertdict` | dict |
| 1.82% | `python` | `find_empty_slot` | dict |
| 1.53% | `python` | `unicode_dealloc` | memory |
| 1.28% | `[JIT]` | `jit` | jit |
| 1.23% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 1.10% | `python` | `build_indices_unicode` | dict |
| 1.02% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.92% | `python` | `_Py_Dealloc` | memory |
| 0.87% | `python` | `unicode_hash` | str |
| 0.72% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.66% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.64% | `python` | `_Py_NewReference` | memory |
| 0.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.56% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `dictresize` | dict |
| 0.46% | `python` | `maybe_small_long` | unknown |
| 0.46% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.45% | `python` | `PyBytes_FromStringAndSize` | str |
| 0.44% | `python` | `PyObject_Hash` | dynamic |
| 0.42% | `libc.so.6` | `_int_malloc` | libc |
| 0.39% | `python` | `new_keys_object` | dict |
| 0.37% | `python` | `Py_HashBuffer` | unknown |
| 0.35% | `python` | `PyObject_Malloc` | dynamic |
| 0.35% | `python` | `sre_ucs1_match` | library |
| 0.34% | `python` | `PyObject_Free` | dynamic |
| 0.31% | `python` | `long_alloc` | memory |
| 0.30% | `python` | `pattern_new_match` | memory |
| 0.30% | `python` | `insert_to_emptydict` | dict |
| 0.30% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `_json.cpython-316-x86_64-linux-gnu.so` | `PyUnicode_Substring@plt` | library |
| 0.29% | `libc.so.6` | `malloc` | libc |
| 0.28% | `python` | `py_dealloc` | memory |
| 0.27% | `python` | `_PyObject_Realloc` | memory |
| 0.27% | `python` | `memcpy@plt` | memory |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.34% | `[JIT]` | `jit` | jit |
| 5.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.66% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.77% | `python` | `initialize_locals` | interpreter |
| 2.60% | `python` | `_Py_dict_lookup` | lookup |
| 2.45% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.14% | `python` | `PyDict_New` | memory |
| 2.12% | `python` | `_PyObject_Malloc` | memory |
| 2.03% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.99% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.90% | `python` | `_PyCode_CheckLineNumber` | interpreter |
| 1.74% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 1.71% | `python` | `dict_dealloc` | memory |
| 1.41% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 1.29% | `python` | `py_dealloc` | memory |
| 1.27% | `python` | `_PyObject_Free` | memory |
| 1.25% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.11% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.10% | `python` | `_Py_Dealloc` | memory |
| 1.07% | `python` | `_PyDict_SubscriptKnownHash` | dict |
| 0.80% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.79% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.79% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.77% | `python` | `PyUnicode_Format` | str |
| 0.69% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.68% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.65% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.64% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.55% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.54% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.52% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.49% | `python` | `_Py_NewReference` | memory |
| 0.43% | `python` | `asciilib_default_find` | unknown |
| 0.40% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `_PyLong_Frexp` | int |
| 0.38% | `python` | `l_mod` | int |
| 0.33% | `python` | `PyType_IsSubtype` | dynamic |
| 0.31% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.31% | `python` | `_PyType_GetDict` | dynamic |
| 0.30% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.30% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.30% | `python` | `any_find_slice` | unknown |
| 0.29% | `python` | `dict_get` | dict |
| 0.28% | `python` | `make_dict_from_instance_attributes` | unknown |
| 0.28% | `python` | `asciilib_fastsearch.constprop.1` | unknown |
| 0.27% | `[kernel.kallsyms]` | `__task_pid_nr_ns` | kernel |
| 0.27% | `python` | `unicode_rfind` | str |
| 0.27% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.26% | `python` | `PyUnicode_AsUCS4` | str |
| 0.26% | `python` | `_PyEval_Vector` | interpreter |
| 0.25% | `python` | `PyUnicode_New.part.0` | memory |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.50% | `[JIT]` | `jit` | jit |
| 9.57% | `python` | `replace` | str |
| 5.79% | `python` | `long_to_decimal_string_internal` | int |
| 5.48% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 5.16% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 5.02% | `python` | `unicode_replace` | str |
| 4.88% | `python` | `_PyObject_Malloc` | memory |
| 3.67% | `python` | `_PyObject_Free` | memory |
| 3.25% | `python` | `deque_append` | miscobj |
| 2.66% | `python` | `dequeiter_next` | miscobj |
| 1.86% | `python` | `PyObject_Str` | dynamic |
| 1.84% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.72% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.68% | `python` | `PyUnicode_New` | memory |
| 1.46% | `python` | `_list_extend` | list |
| 1.38% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.18% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 1.08% | `python` | `_PyRunRemoteDebugger` | unknown |
| 1.05% | `python` | `deque_clear.part.0` | miscobj |
| 1.04% | `python` | `list_dealloc` | memory |
| 1.02% | `python` | `PyThread_get_thread_ident` | threading |
| 0.83% | `python` | `long_alloc` | memory |
| 0.81% | `python` | `sre_search` | library |
| 0.72% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.70% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.67% | `python` | `_Py_IsMainThread` | unknown |
| 0.62% | `python` | `unicode_dealloc` | memory |
| 0.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.61% | `python` | `PyLong_FromLong` | int |
| 0.52% | `python` | `long_to_decimal_string` | int |
| 0.41% | `python` | `_Py_NewReference` | memory |
| 0.38% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.38% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.34% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.34% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.31% | `python` | `PyObject_Malloc` | dynamic |
| 0.30% | `python` | `memcpy@plt` | memory |
| 0.27% | `python` | `PyObject_Free` | dynamic |
| 0.27% | `libc.so.6` | `_int_malloc` | libc |
| 0.26% | `python` | `_Py_Dealloc` | memory |
| 0.26% | `python` | `_PyInterpreterState_GetConfig` | unknown |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.50% | `[JIT]` | `jit` | jit |
| 11.66% | `python` | `_Py_dict_lookup` | lookup |
| 10.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.57% | `python` | `PyObject_RichCompareBool` | dynamic |
| 4.87% | `python` | `tuple_richcompare` | tuple |
| 3.18% | `python` | `_PyDict_Subscript` | dict |
| 2.49% | `python` | `_PyLong_GCD` | int |
| 1.59% | `python` | `gen_iternext` | miscobj |
| 1.56% | `python` | `_PyObject_Free` | memory |
| 1.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.34% | `python` | `_PyObject_Malloc` | memory |
| 1.33% | `python` | `builtin_sum` | unknown |
| 1.12% | `python` | `tuple_hash` | tuple |
| 1.05% | `python` | `PyDict_GetItemRef` | dict |
| 1.02% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.86% | `python` | `py_dealloc` | memory |
| 0.83% | `python` | `_PyJIT_Entry` | compiler |
| 0.74% | `python` | `_Py_Dealloc` | memory |
| 0.70% | `python` | `insertdict` | dict |
| 0.68% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.63% | `python` | `PyObject_Hash` | dynamic |
| 0.63% | `python` | `subtype_dealloc` | memory |
| 0.62% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 0.61% | `python` | `set_lookkey` | miscobj |
| 0.55% | `python` | `long_div` | int |
| 0.53% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.52% | `python` | `func_clear` | unknown |
| 0.52% | `python` | `_PySuper_LookupDescr` | unknown |
| 0.51% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.50% | `python` | `_PyCompactLong_Multiply` | unknown |
| 0.49% | `python` | `gen_dealloc` | memory |
| 0.46% | `python` | `PyFloat_FromDouble` | float |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.43% | `python` | `PyIter_Next` | dynamic |
| 0.42% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.39% | `python` | `PyLong_FromLong` | int |
| 0.39% | `python` | `initialize_locals` | interpreter |
| 0.38% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.34% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.34% | `python` | `func_dealloc` | memory |
| 0.33% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.30% | `python` | `_PyEval_Vector` | interpreter |
| 0.30% | `python` | `min_max` | unknown |
| 0.29% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `tp_new_wrapper` | memory |
| 0.28% | `python` | `tuple_alloc` | memory |
| 0.28% | `python` | `PyNumber_FloorDivide` | dynamic |
| 0.27% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `python` | `PyType_IsSubtype` | dynamic |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.34% | `[JIT]` | `jit` | jit |
| 12.23% | `python` | `set_lookkey` | miscobj |
| 11.17% | `python` | `set_issubset_impl` | miscobj |
| 9.75% | `python` | `setiter_iternext` | miscobj |
| 4.12% | `python` | `set_dealloc` | memory |
| 3.93% | `python` | `set_difference_untracked` | miscobj |
| 3.45% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.92% | `python` | `set_add_entry_takeref` | miscobj |
| 2.38% | `python` | `_PyObject_Free` | memory |
| 2.16% | `python` | `_PyObject_Malloc` | memory |
| 2.09% | `python` | `long_richcompare` | int |
| 1.90% | `python` | `list_slice_lock_held` | list |
| 1.76% | `python` | `list_dealloc` | memory |
| 1.58% | `python` | `min_max` | unknown |
| 1.43% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.35% | `python` | `set_intersection` | miscobj |
| 1.28% | `python` | `set_table_resize` | miscobj |
| 1.27% | `python` | `PyObject_RichCompare` | dynamic |
| 1.11% | `python` | `PyIter_Next` | dynamic |
| 1.07% | `python` | `set_merge_lock_held` | miscobj |
| 0.96% | `python` | `py_dealloc` | memory |
| 0.88% | `python` | `set_richcompare` | miscobj |
| 0.79% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.59% | `python` | `set_difference_update_internal` | miscobj |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.49% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.48% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.46% | `python` | `PyList_New.constprop.0` | memory |
| 0.43% | `python` | `list_ass_slice_lock_held` | list |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.39% | `python` | `PyObject_Size` | dynamic |
| 0.37% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.34% | `python` | `set_iter` | miscobj |
| 0.33% | `python` | `_Py_Dealloc` | memory |
| 0.33% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `python` | `set_sub` | miscobj |
| 0.31% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.30% | `python` | `list_slice_wrap` | list |
| 0.29% | `python` | `setiter_dealloc` | memory |
| 0.29% | `python` | `PySlice_Unpack` | miscobj |
| 0.26% | `python` | `_PyList_SliceSubscript` | list |
| 0.26% | `python` | `PyObject_IsTrue` | dynamic |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 68.26% | `[JIT]` | `jit` | jit |
| 8.48% | `python` | `PyFloat_FromDouble` | float |
| 7.59% | `libm.so.6` | `__ieee754_pow_fma` | library |
| 3.86% | `python` | `float_dealloc` | memory |
| 2.97% | `python` | `_Py_NewReference` | memory |
| 2.57% | `python` | `_Py_Dealloc` | memory |
| 2.32% | `python` | `float_pow` | float |
| 1.00% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.89% | `python` | `_PyNumber_PowerNoMod` | dynamic |
| 0.80% | `libm.so.6` | `pow@@GLIBC_2.29` | library |
| 0.31% | `python` | `_PyEval_EvalFrameDefault` | interpreter |

## networkx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.52% | `python` | `set_lookkey` | miscobj |
| 21.16% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 15.27% | `python` | `dictiter_iternextkey` | dict |
| 9.36% | `[JIT]` | `jit` | jit |
| 5.90% | `python` | `build_indices_unicode` | dict |
| 2.62% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.32% | `python` | `_PyDict_Subscript` | dict |
| 1.16% | `python` | `set_dealloc` | memory |
| 1.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.95% | `python` | `_PySet_Contains` | miscobj |
| 0.93% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.83% | `python` | `list_dealloc` | memory |
| 0.82% | `python` | `unicode_hash` | str |
| 0.80% | `python` | `deque_clear.part.0` | miscobj |
| 0.58% | `python` | `set_table_resize` | miscobj |
| 0.56% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.53% | `python` | `_Py_dict_lookup` | lookup |
| 0.51% | `python` | `PyObject_Hash` | dynamic |
| 0.44% | `python` | `set_add_entry_takeref` | miscobj |
| 0.44% | `python` | `_PyObject_Free` | memory |
| 0.41% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.38% | `python` | `insertdict` | dict |
| 0.35% | `python` | `merge_from_seq2_lock_held` | unknown |
| 0.32% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.31% | `python` | `py_dealloc` | memory |

## networkx_connected_components

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.86% | `python` | `set_lookkey` | miscobj |
| 16.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 15.87% | `python` | `dictiter_iternextkey` | dict |
| 10.88% | `[JIT]` | `jit` | jit |
| 3.47% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 2.59% | `python` | `_PyDict_Subscript` | dict |
| 2.52% | `python` | `set_dealloc` | memory |
| 1.65% | `python` | `set_merge_lock_held` | miscobj |
| 1.18% | `python` | `_PySet_Contains` | miscobj |
| 1.02% | `python` | `unicode_hash` | str |
| 0.94% | `python` | `list_dealloc` | memory |
| 0.68% | `python` | `set_table_resize` | miscobj |
| 0.66% | `python` | `PyObject_Hash` | dynamic |
| 0.60% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.51% | `python` | `set_add_entry_takeref` | miscobj |
| 0.51% | `python` | `_PyObject_Free` | memory |
| 0.45% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.30% | `python` | `_Py_dict_lookup` | lookup |

## networkx_k_core

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.81% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 12.92% | `[JIT]` | `jit` | jit |
| 7.51% | `python` | `list_remove` | list |
| 5.86% | `python` | `_PyDict_Subscript` | dict |
| 3.86% | `python` | `dictiter_iternextkey` | dict |
| 3.78% | `python` | `visit_decref` | gc |
| 3.40% | `python` | `visit_reachable` | gc |
| 3.29% | `python` | `_Py_dict_lookup` | lookup |
| 1.69% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.58% | `python` | `build_indices_unicode` | dict |
| 1.43% | `python` | `dict_traverse` | gc |
| 1.34% | `python` | `PyUnicode_RichCompare` | str |
| 1.32% | `python` | `list_dealloc` | memory |
| 1.21% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.03% | `python` | `insertdict` | dict |
| 0.98% | `python` | `listiter_next` | list |
| 0.92% | `python` | `gc_collect_main` | gc |
| 0.68% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.51% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.45% | `python` | `list_traverse` | gc |
| 0.40% | `python` | `_PyObject_Malloc` | memory |
| 0.38% | `python` | `list_sort_impl` | list |
| 0.35% | `python` | `list_ass_slice_lock_held` | list |
| 0.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.27% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.26% | `python` | `_PyDict_Next` | dict |
| 0.26% | `python` | `dictiter_iternextitem` | dict |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.68% | `[JIT]` | `jit` | jit |
| 4.44% | `python` | `_PyObject_Malloc` | memory |
| 4.05% | `python` | `_PyObject_Free` | memory |
| 3.64% | `python` | `set_add_entry_takeref` | miscobj |
| 3.23% | `python` | `PySlice_AdjustIndices` | miscobj |
| 2.70% | `python` | `py_dealloc` | memory |
| 1.80% | `python` | `set_dealloc` | memory |
| 1.70% | `python` | `PyList_New.constprop.0` | memory |
| 1.61% | `python` | `_PyCompactLong_Add` | unknown |
| 1.24% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.20% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.16% | `python` | `list_dealloc` | memory |
| 1.15% | `python` | `PyLong_FromLong` | int |
| 1.07% | `python` | `_Py_Dealloc` | memory |
| 1.02% | `python` | `_PyDict_LoadBuiltinsFromGlobals` | dict |
| 1.01% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.98% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.92% | `python` | `list_ass_slice_lock_held` | list |
| 0.89% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.89% | `python` | `func_clear` | unknown |
| 0.87% | `python` | `set_table_resize` | miscobj |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.83% | `python` | `make_range_object` | unknown |
| 0.82% | `python` | `list_slice_lock_held` | list |
| 0.78% | `python` | `_PyList_BinarySlice` | list |
| 0.75% | `python` | `list_ass_subscript` | list |
| 0.73% | `python` | `gen_dealloc` | memory |
| 0.73% | `python` | `tuple_dealloc` | memory |
| 0.72% | `python` | `func_dealloc` | memory |
| 0.69% | `python` | `_PyObject_Realloc` | memory |
| 0.69% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.68% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 0.64% | `python` | `_Py_NewReference` | memory |
| 0.64% | `python` | `range_iter` | miscobj |
| 0.63% | `python` | `PyLong_AsLong` | int |
| 0.59% | `python` | `range_reverse` | miscobj |
| 0.59% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.56% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.52% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.51% | `python` | `make_gen` | miscobj |
| 0.51% | `python` | `PyObject_Hash` | dynamic |
| 0.48% | `python` | `_PySet_AddTakeRef` | miscobj |
| 0.47% | `python` | `long_hash` | int |
| 0.47% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.46% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.45% | `python` | `PyObject_GC_Del` | gc |
| 0.43% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.41% | `python` | `_Py_dict_lookup` | lookup |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `_PyList_Concat` | list |
| 0.39% | `python` | `_PyObject_GC_New` | gc |
| 0.39% | `python` | `PyCMethod_New` | memory |
| 0.38% | `python` | `PyDict_GetItemRef` | dict |
| 0.37% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.37% | `python` | `PySequence_Fast` | dynamic |
| 0.36% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.35% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.33% | `python` | `PyObject_SetItem` | dynamic |
| 0.31% | `python` | `reversed_new_impl` | memory |
| 0.27% | `python` | `list_subscript` | list |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 5.71% | `[JIT]` | `jit` | jit |
| 3.91% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 3.86% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 3.78% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 3.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.54% | `python` | `_PyObject_Malloc` | memory |
| 3.05% | `python` | `_PyObject_Free` | memory |
| 2.08% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 1.74% | `[kernel.kallsyms]` | `ext4_htree_store_dirent` | kernel |
| 1.64% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 1.57% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 1.42% | `[kernel.kallsyms]` | `link_path_walk.part.0.constprop.0` | kernel |
| 1.31% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.28% | `[kernel.kallsyms]` | `filldir64` | kernel |
| 1.25% | `[kernel.kallsyms]` | `half_md4_transform.isra.0` | kernel |
| 1.12% | `python` | `initialize_locals` | interpreter |
| 1.11% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.08% | `python` | `take_gil` | gil |
| 1.06% | `python` | `ScandirIterator_iternext` | unknown |
| 0.99% | `python` | `PyLong_FromLongLong` | int |
| 0.96% | `python` | `_Py_Dealloc` | memory |
| 0.94% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.76% | `[kernel.kallsyms]` | `str2hashbuf_signed` | kernel |
| 0.71% | `[kernel.kallsyms]` | `__kmalloc` | kernel |
| 0.67% | `python` | `sre_ucs1_match` | library |
| 0.66% | `python` | `_pystat_fromstructstat` | unknown |
| 0.63% | `python` | `clear_slots` | unknown |
| 0.63% | `libc.so.6` | `_int_malloc` | libc |
| 0.61% | `python` | `py_dealloc` | memory |
| 0.61% | `[kernel.kallsyms]` | `kmem_cache_alloc` | kernel |
| 0.61% | `libc.so.6` | `__GI___readdir64` | libc |
| 0.60% | `[kernel.kallsyms]` | `cp_new_stat` | kernel |
| 0.60% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.57% | `[kernel.kallsyms]` | `filename_lookup` | kernel |
| 0.56% | `[kernel.kallsyms]` | `strncpy_from_user` | kernel |
| 0.55% | `[kernel.kallsyms]` | `apparmor_inode_getattr` | kernel |
| 0.55% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.52% | `[kernel.kallsyms]` | `__virt_addr_valid` | kernel |
| 0.50% | `[kernel.kallsyms]` | `generic_permission` | kernel |
| 0.50% | `python` | `_PyEval_Vector` | interpreter |
| 0.49% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.49% | `[kernel.kallsyms]` | `kfree` | kernel |
| 0.49% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.49% | `[kernel.kallsyms]` | `rb_insert_color` | kernel |
| 0.48% | `[kernel.kallsyms]` | `ext4_file_getattr` | kernel |
| 0.48% | `python` | `_PyJIT_Entry` | compiler |
| 0.48% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.48% | `[kernel.kallsyms]` | `__slab_free` | kernel |
| 0.47% | `python` | `structseq_dealloc` | memory |
| 0.47% | `[kernel.kallsyms]` | `security_inode_getattr` | kernel |
| 0.46% | `[kernel.kallsyms]` | `set_root` | kernel |
| 0.46% | `[kernel.kallsyms]` | `inode_permission` | kernel |
| 0.45% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.44% | `python` | `_Py_NewReference` | memory |
| 0.44% | `[kernel.kallsyms]` | `rb_next` | kernel |
| 0.43% | `[kernel.kallsyms]` | `do_syscall_64` | kernel |
| 0.41% | `python` | `subtype_dealloc` | memory |
| 0.41% | `python` | `_PyLong_FromMedium` | int |
| 0.40% | `[kernel.kallsyms]` | `map_id_up` | kernel |
| 0.40% | `[kernel.kallsyms]` | `__ext4fs_dirhash` | kernel |
| 0.40% | `python` | `find_first_nonascii` | str |
| 0.39% | `[kernel.kallsyms]` | `__ext4_check_dir_entry` | kernel |
| 0.39% | `[kernel.kallsyms]` | `common_perm_cond` | kernel |
| 0.39% | `[kernel.kallsyms]` | `vfs_getattr_nosec` | kernel |
| 0.38% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.37% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.36% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.35% | `[kernel.kallsyms]` | `kmem_cache_free` | kernel |
| 0.35% | `python` | `tuple_alloc` | memory |
| 0.35% | `[kernel.kallsyms]` | `ext4_getattr` | kernel |
| 0.34% | `[kernel.kallsyms]` | `security_inode_permission` | kernel |
| 0.34% | `libc.so.6` | `__GI___fstatat64` | libc |
| 0.34% | `[kernel.kallsyms]` | `step_into` | kernel |
| 0.34% | `[kernel.kallsyms]` | `memchr` | kernel |
| 0.34% | `python` | `long_dealloc` | memory |
| 0.33% | `python` | `_Py_dict_lookup` | lookup |
| 0.33% | `[kernel.kallsyms]` | `htree_dirblock_to_tree` | kernel |
| 0.33% | `[kernel.kallsyms]` | `call_filldir` | kernel |
| 0.33% | `[kernel.kallsyms]` | `vfs_statx` | kernel |
| 0.33% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.32% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.32% | `python` | `tuple_dealloc` | memory |
| 0.31% | `[kernel.kallsyms]` | `__do_sys_newfstatat` | kernel |
| 0.31% | `python` | `PyDict_GetItemWithError` | dict |
| 0.31% | `[kernel.kallsyms]` | `__check_heap_object` | kernel |
| 0.31% | `[kernel.kallsyms]` | `slab_update_freelist.isra.0` | kernel |
| 0.30% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.30% | `[kernel.kallsyms]` | `_copy_to_user` | kernel |
| 0.30% | `python` | `fill_time` | unknown |
| 0.30% | `python` | `os_stat` | unknown |
| 0.30% | `python` | `PyUnicode_New.part.0` | memory |
| 0.29% | `[kernel.kallsyms]` | `__legitimize_mnt` | kernel |
| 0.29% | `python` | `PyThread_get_thread_ident` | threading |
| 0.29% | `python` | `tp_new_wrapper` | memory |
| 0.29% | `python` | `PyStructSequence_SetItem` | unknown |
| 0.28% | `[kernel.kallsyms]` | `path_lookupat` | kernel |
| 0.28% | `python` | `PyLong_FromUnsignedLong` | int |
| 0.28% | `python` | `path_converter` | unknown |
| 0.28% | `python` | `PyDict_GetItemRef` | dict |
| 0.28% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.28% | `python` | `PyDict_New` | memory |
| 0.28% | `[kernel.kallsyms]` | `rb_next_postorder` | kernel |
| 0.28% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.27% | `python` | `slot_tp_init` | unknown |
| 0.27% | `python` | `PyLong_FromLong` | int |
| 0.27% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.26% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.26% | `python` | `_PyObject_Call_Prepend` | dynamic |
| 0.26% | `python` | `_PyThreadState_Attach` | threading |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.26% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.26% | `python` | `_PyType_GetDict` | dynamic |
| 0.25% | `python` | `DirEntry_dealloc` | memory |
| 0.25% | `python` | `drop_gil` | gil |

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
| 30.57% | `[JIT]` | `jit` | jit |
| 4.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.19% | `python` | `_Py_dict_lookup` | lookup |
| 4.06% | `python` | `_PyObject_Malloc` | memory |
| 3.81% | `python` | `_PyObject_Free` | memory |
| 3.50% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.80% | `python` | `initialize_locals` | interpreter |
| 1.66% | `python` | `tuple_dealloc` | memory |
| 1.64% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.47% | `libc.so.6` | `__strlen_avx2` | libc |
| 1.35% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.32% | `python` | `PyBuffer_Release` | miscobj |
| 1.23% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.21% | `python` | `_PyTuple_Resize` | tuple |
| 1.21% | `python` | `PyBuffer_FillInfo` | miscobj |
| 1.14% | `python` | `_PyBytes_Concat` | unknown |
| 1.09% | `python` | `write_bytes_lock_held` | unknown |
| 1.01% | `python` | `dict_get` | dict |
| 1.00% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.85% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.83% | `python` | `PyObject_GetBuffer` | dynamic |
| 0.80% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.80% | `python` | `_Py_Dealloc` | memory |
| 0.79% | `python` | `PyLong_FromVoidPtr` | int |
| 0.78% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.75% | `python` | `PyLong_FromSsize_t` | int |
| 0.73% | `_struct.cpython-316-x86_64-linux-gnu.so` | `pack` | library |
| 0.72% | `python` | `PyDict_GetItemRef` | dict |
| 0.69% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.65% | `python` | `PyUnicode_AsEncodedString` | str |
| 0.62% | `python` | `unicode_encode` | str |
| 0.61% | `python` | `sys_audit_tstate` | unknown |
| 0.59% | `_struct.cpython-316-x86_64-linux-gnu.so` | `s_pack_internal` | library |
| 0.58% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.56% | `python` | `tuple_alloc` | memory |
| 0.55% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.54% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.53% | `python` | `PySys_Audit` | unknown |
| 0.51% | `python` | `PyObject_Hash` | dynamic |
| 0.50% | `python` | `insertdict` | dict |
| 0.49% | `python` | `long_hash` | int |
| 0.45% | `python` | `builtin_id` | unknown |
| 0.40% | `python` | `py_dealloc` | memory |
| 0.39% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.39% | `python` | `PyType_GetModuleByDef` | dynamic |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.34% | `python` | `PyObject_Malloc` | dynamic |
| 0.34% | `libc.so.6` | `_int_malloc` | libc |
| 0.34% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.32% | `python` | `PyObject_Size` | dynamic |
| 0.32% | `python` | `_PyObject_Realloc` | memory |
| 0.32% | `python` | `dictiter_iternextitem` | dict |
| 0.29% | `python` | `_PyCallMethodDescriptorFastWithKeywords_StackRef` | unknown |
| 0.28% | `python` | `_PyLong_FromMedium` | int |
| 0.27% | `python` | `PyBytesWriter_Finish` | unknown |
| 0.26% | `python` | `bytes_buffer_getbuffer` | str |
| 0.26% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.25% | `python` | `builtin_getattr` | lookup |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.43% | `python` | `x_divrem` | int |
| 27.94% | `python` | `k_mul` | int |
| 13.68% | `python` | `x_add` | int |
| 6.77% | `python` | `x_sub` | int |
| 2.89% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.82% | `libc.so.6` | `_int_malloc` | libc |
| 0.94% | `[JIT]` | `jit` | jit |
| 0.46% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.36% | `python` | `_PyObject_Free` | memory |
| 0.30% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.27% | `python` | `long_alloc` | memory |
| 0.26% | `libc.so.6` | `malloc` | libc |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.95% | `[JIT]` | `jit` | jit |
| 4.52% | `python` | `_PyObject_Malloc` | memory |
| 4.22% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.44% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.25% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 2.99% | `python` | `_PyObject_Free` | memory |
| 2.41% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.76% | `python` | `long_to_decimal_string_internal` | int |
| 1.75% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.67% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.48% | `python` | `_Py_dict_lookup` | lookup |
| 1.38% | `python` | `PyUnicode_Format` | str |
| 1.29% | `python` | `_Py_type_getattro_stackref` | unknown |
| 1.27% | `python` | `PyObject_IsSubclass` | dynamic |
| 1.25% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.99% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.99% | `python` | `set_lookkey` | miscobj |
| 0.96% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.95% | `python` | `tuple_alloc` | memory |
| 0.84% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.79% | `python` | `py_dealloc` | memory |
| 0.74% | `python` | `_Py_Dealloc` | memory |
| 0.72% | `python` | `list_sort_impl` | list |
| 0.70% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.69% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.66% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.65% | `python` | `PyUnicode_New` | memory |
| 0.63% | `python` | `_PyObject_Realloc` | memory |
| 0.62% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.62% | `python` | `list_append` | list |
| 0.60% | `python` | `PyType_IsSubtype` | dynamic |
| 0.57% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.55% | `python` | `PyObject_Repr` | dynamic |
| 0.55% | `python` | `initialize_locals` | interpreter |
| 0.53% | `python` | `PyNumber_Remainder` | dynamic |
| 0.53% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.49% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.48% | `python` | `unicode_dealloc` | memory |
| 0.45% | `python` | `_Py_NewReference` | memory |
| 0.45% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.45% | `python` | `builtin_issubclass` | unknown |
| 0.43% | `python` | `tuple_dealloc` | memory |
| 0.42% | `python` | `_PyRunRemoteDebugger` | unknown |
| 0.42% | `python` | `_PyUnicodeWriter_WriteSubstring` | str |
| 0.41% | `python` | `PyList_New.constprop.0` | memory |
| 0.41% | `python` | `recursive_issubclass` | unknown |
| 0.40% | `python` | `_PySet_Contains` | miscobj |
| 0.38% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.38% | `python` | `PyCMethod_New` | memory |
| 0.37% | `python` | `subtype_dealloc` | memory |
| 0.37% | `python` | `PyObject_Hash` | dynamic |
| 0.37% | `python` | `list_dealloc` | memory |
| 0.35% | `python` | `_PyStaticType_GetState` | unknown |
| 0.35% | `python` | `PyThread_get_thread_ident` | threading |
| 0.34% | `python` | `delitem_common` | dynamic |
| 0.34% | `python` | `_PyStolenTuple_Free` | unknown |
| 0.34% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.33% | `python` | `PyObject_DelItem` | dynamic |
| 0.33% | `python` | `sys_audit_tstate` | unknown |
| 0.33% | `python` | `insertdict` | dict |
| 0.33% | `python` | `_PyForIter_VirtualIteratorNext` | unknown |
| 0.33% | `python` | `_Py_BuildString_StackRefSteal` | unknown |
| 0.32% | `python` | `PyUnicode_New.part.0` | memory |
| 0.32% | `python` | `slot_tp_richcompare` | dynamic |
| 0.32% | `python` | `unicode_repr` | str |
| 0.31% | `python` | `builtin_getattr` | lookup |
| 0.30% | `python` | `long_hash` | int |
| 0.27% | `python` | `_PyEval_Vector` | interpreter |
| 0.27% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.26% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.92% | `[JIT]` | `jit` | jit |
| 11.29% | `python` | `sre_ucs1_match` | library |
| 9.11% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.75% | `python` | `gc_collect_main` | gc |
| 2.55% | `python` | `_Py_dict_lookup` | lookup |
| 2.19% | `python` | `_PyObject_Malloc` | memory |
| 2.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.98% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.58% | `python` | `_PyObject_Free` | memory |
| 1.49% | `python` | `_PyDict_Subscript` | dict |
| 1.36% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.30% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.17% | `libc.so.6` | `_int_malloc` | libc |
| 0.90% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.87% | `python` | `initialize_locals` | interpreter |
| 0.86% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.81% | `python` | `pattern_new_match` | memory |
| 0.81% | `python` | `visit_decref` | gc |
| 0.80% | `python` | `_PyJIT_Entry` | compiler |
| 0.76% | `python` | `list_ass_slice_lock_held` | list |
| 0.75% | `python` | `py_dealloc` | memory |
| 0.74% | `python` | `subtype_traverse` | gc |
| 0.73% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.72% | `python` | `PySlice_New` | memory |
| 0.71% | `python` | `dict_get` | dict |
| 0.70% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.66% | `python` | `visit_reachable` | gc |
| 0.65% | `python` | `sre_ucs1_count` | library |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `_Py_Dealloc` | memory |
| 0.57% | `libc.so.6` | `malloc` | libc |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.54% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.54% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.52% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.50% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.48% | `python` | `list_ass_subscript` | list |
| 0.48% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.47% | `python` | `subtype_dealloc` | memory |
| 0.43% | `python` | `long_neg_method` | int |
| 0.42% | `python` | `_PyEval_Vector` | interpreter |
| 0.40% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.38% | `python` | `PyObject_DelItem` | dynamic |
| 0.34% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.33% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.32% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.32% | `python` | `PyNumber_Negative` | dynamic |
| 0.32% | `python` | `PyType_IsSubtype` | dynamic |
| 0.32% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.32% | `python` | `PyUnicode_Contains` | str |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.31% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.31% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.29% | `python` | `list_subscript` | list |
| 0.29% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.29% | `python` | `PySlice_Unpack` | miscobj |
| 0.28% | `python` | `PyObject_IsInstance` | dynamic |
| 0.28% | `python` | `PyList_New.constprop.0` | memory |
| 0.27% | `python` | `PyDict_Contains` | dict |
| 0.27% | `python` | `slot_mp_ass_subscript` | unknown |
| 0.26% | `python` | `PyObject_SetItem` | dynamic |
| 0.26% | `python` | `type_call` | dynamic |
| 0.25% | `libc.so.6` | `_int_free` | libc |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.21% | `[JIT]` | `jit` | jit |
| 5.34% | `python` | `list_dealloc` | memory |
| 4.44% | `python` | `list_ass_slice_lock_held` | list |
| 3.14% | `python` | `_PyList_Concat` | list |
| 2.36% | `python` | `list_slice_lock_held` | list |
| 2.11% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 2.05% | `python` | `_PyCompactLong_Add` | unknown |
| 1.88% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.82% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.75% | `libc.so.6` | `_int_malloc` | libc |
| 1.73% | `python` | `_PyObject_Malloc` | memory |
| 1.72% | `python` | `stringlib_bytes_join_lock_held` | str |
| 1.62% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.46% | `python` | `bytes_subscript` | str |
| 1.41% | `python` | `PyLong_AsNativeBytes.constprop.0` | int |
| 1.24% | `python` | `list_sort_impl` | list |
| 1.23% | `python` | `long_lshift_method` | int |
| 1.15% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.09% | `python` | `_PyLong_FromMedium` | int |
| 1.04% | `python` | `PyLong_AsSsize_t` | int |
| 0.96% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.90% | `python` | `PyBuffer_Release` | miscobj |
| 0.88% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.87% | `python` | `long_lshift1` | int |
| 0.85% | `python` | `PyNumber_Lshift` | dynamic |
| 0.81% | `python` | `unsafe_long_compare` | unknown |
| 0.71% | `python` | `_Py_Dealloc` | memory |
| 0.71% | `python` | `PySlice_New` | memory |
| 0.70% | `python` | `long_rshift` | int |
| 0.65% | `python` | `PyLong_FromSsize_t` | int |
| 0.65% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.64% | `python` | `py_dealloc` | memory |
| 0.62% | `python` | `PyObject_GetItem` | dynamic |
| 0.59% | `python` | `long_dealloc` | memory |
| 0.59% | `python` | `PyList_New.constprop.0` | memory |
| 0.57% | `python` | `_PyEval_SliceIndex` | interpreter |
| 0.56% | `python` | `_Py_NewReference` | memory |
| 0.49% | `python` | `PyNumber_Rshift` | dynamic |
| 0.46% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.46% | `libc.so.6` | `unlink_chunk.isra.0` | libc |
| 0.45% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.38% | `python` | `long_rshift1` | int |
| 0.34% | `python` | `enum_next` | miscobj |
| 0.34% | `python` | `_PyList_BinarySlice` | list |
| 0.34% | `libc.so.6` | `malloc` | libc |
| 0.33% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.33% | `python` | `gallop_right` | unknown |
| 0.32% | `python` | `gallop_left` | unknown |
| 0.28% | `python` | `PyObject_Size` | dynamic |

## pylint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.51% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.22% | `[JIT]` | `jit` | jit |
| 2.81% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.72% | `python` | `_PyObject_Malloc` | memory |
| 2.59% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.33% | `python` | `gc_collect_main` | gc |
| 1.71% | `python` | `visit_reachable` | gc |
| 1.70% | `python` | `_PyObject_Free` | memory |
| 1.70% | `python` | `visit_decref` | gc |
| 1.66% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.54% | `python` | `initialize_locals` | interpreter |
| 1.53% | `python` | `_Py_dict_lookup` | lookup |
| 1.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.93% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.83% | `python` | `PyDict_GetItemRef` | dict |
| 0.80% | `python` | `py_dealloc` | memory |
| 0.73% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.67% | `python` | `unicode_repr` | str |
| 0.64% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.64% | `python` | `insertdict` | dict |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.60% | `python` | `tuple_dealloc` | memory |
| 0.60% | `python` | `subtype_traverse` | gc |
| 0.60% | `python` | `listiter_next` | list |
| 0.59% | `python` | `PyType_IsSubtype` | dynamic |
| 0.59% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.51% | `python` | `dict_traverse` | gc |
| 0.50% | `python` | `PyObject_SetAttr` | dynamic |
| 0.48% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.48% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.47% | `python` | `partial_vectorcall` | unknown |
| 0.46% | `python` | `_PyEval_Vector` | interpreter |
| 0.45% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.44% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.43% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.43% | `python` | `_Py_Dealloc` | memory |
| 0.42% | `python` | `_PyLexer_get_normal` | unknown |
| 0.41% | `python` | `islice_next` | unknown |
| 0.41% | `python` | `tuple_alloc` | memory |
| 0.40% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.40% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.38% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.36% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.34% | `python` | `sre_ucs1_match` | library |
| 0.34% | `python` | `_PyPegen_expect_token` | interpreter |
| 0.33% | `python` | `list_traverse` | gc |
| 0.31% | `python` | `_PyDict_FromItems` | dict |
| 0.30% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.30% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.29% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.28% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.28% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.26% | `python` | `_PyObject_GC_New` | gc |
| 0.26% | `python` | `do_mkvalue` | unknown |
| 0.26% | `python` | `PyDict_Next` | dict |
| 0.25% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.25% | `python` | `object_isinstance` | dynamic |
| 0.25% | `python` | `_PyThreadState_PopFrame` | threading |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.28% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.98% | `python` | `gc_collect_main` | gc |
| 2.95% | `python` | `_PyObject_Malloc` | memory |
| 2.54% | `python` | `visit_decref` | gc |
| 2.20% | `python` | `visit_reachable` | gc |
| 1.98% | `python` | `_Py_dict_lookup` | lookup |
| 1.88% | `python` | `r_object` | import |
| 1.71% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.54% | `python` | `_PyObject_Free` | memory |
| 1.38% | `python` | `_PyCode_Quicken` | interpreter |
| 1.31% | `python` | `type_ready` | dynamic |
| 1.30% | `python` | `find_name_in_mro` | lookup |
| 1.13% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.07% | `python` | `dict_traverse` | gc |
| 1.06% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.02% | `python` | `siphash13` | str |
| 0.91% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.86% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.83% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.73% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.73% | `python` | `update_one_slot` | lookup |
| 0.71% | `python` | `insertdict` | dict |
| 0.65% | `python` | `tuple_dealloc` | memory |
| 0.65% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.63% | `libc.so.6` | `_int_malloc` | libc |
| 0.62% | `python` | `intern_constants` | str |
| 0.55% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.55% | `python` | `_Py_Dealloc` | memory |
| 0.54% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.52% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.51% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.50% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.48% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.48% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.47% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.43% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.43% | `python` | `PyDict_GetItemRef` | dict |
| 0.43% | `python` | `PyUnicode_New.part.0` | memory |
| 0.43% | `python` | `find_first_nonascii` | str |
| 0.42% | `python` | `py_dealloc` | memory |
| 0.39% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.38% | `python` | `_PyCode_New` | interpreter |
| 0.38% | `python` | `build_indices_unicode` | dict |
| 0.38% | `python` | `initialize_locals` | interpreter |
| 0.37% | `python` | `find_empty_slot` | dict |
| 0.37% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.36% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.36% | `python` | `_PyTypeCache_Insert` | unknown |
| 0.34% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.34% | `python` | `r_long` | import |
| 0.34% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.31% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.30% | `python` | `tuple_traverse` | gc |
| 0.30% | `python` | `code_dealloc` | memory |
| 0.29% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.29% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.28% | `python` | `type_new` | memory |
| 0.28% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.27% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.27% | `python` | `PyType_IsSubtype` | dynamic |
| 0.26% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 0.26% | `python` | `unicode_dealloc` | memory |
| 0.26% | `python` | `tuple_alloc` | memory |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.06% | `python` | `gc_collect_main` | gc |
| 2.81% | `python` | `_PyObject_Malloc` | memory |
| 2.57% | `python` | `visit_decref` | gc |
| 2.35% | `python` | `visit_reachable` | gc |
| 2.28% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 1.78% | `python` | `_Py_dict_lookup` | lookup |
| 1.62% | `python` | `type_ready` | dynamic |
| 1.60% | `python` | `r_object` | import |
| 1.44% | `python` | `_PyObject_Free` | memory |
| 1.32% | `python` | `_PyCode_Quicken` | interpreter |
| 1.19% | `python` | `_Py_hashtable_get_entry_generic` | lookup |
| 1.16% | `python` | `find_name_in_mro` | lookup |
| 1.15% | `python` | `siphash13` | str |
| 1.10% | `python` | `dict_traverse` | gc |
| 1.06% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.88% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.84% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.79% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.77% | `python` | `insertdict` | dict |
| 0.74% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.72% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.71% | `libc.so.6` | `_int_malloc` | libc |
| 0.69% | `ld-linux-x86-64.so.2` | `_dl_relocate_object` | library |
| 0.62% | `python` | `tuple_dealloc` | memory |
| 0.61% | `python` | `update_one_slot` | lookup |
| 0.61% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.58% | `python` | `intern_constants` | str |
| 0.58% | `python` | `dict_setdefault_ref_lock_held` | dict |
| 0.58% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.52% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.51% | `python` | `find_first_nonascii` | str |
| 0.51% | `[kernel.kallsyms]` | `next_uptodate_folio` | kernel |
| 0.50% | `python` | `build_indices_unicode` | dict |
| 0.49% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.49% | `python` | `_Py_Dealloc` | memory |
| 0.48% | `python` | `_Py_dict_lookup_threadsafe_stackref` | lookup |
| 0.47% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.46% | `python` | `_PyUnicode_InternImmortal` | str |
| 0.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.45% | `python` | `PyUnicode_New.part.0` | memory |
| 0.44% | `ld-linux-x86-64.so.2` | `do_lookup_x` | library |
| 0.43% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.41% | `python` | `find_empty_slot` | dict |
| 0.39% | `python` | `py_dealloc` | memory |
| 0.39% | `[kernel.kallsyms]` | `copy_page` | kernel |
| 0.38% | `[kernel.kallsyms]` | `filemap_map_pages` | kernel |
| 0.36% | `[kernel.kallsyms]` | `__handle_mm_fault` | kernel |
| 0.35% | `python` | `_PyCode_New` | interpreter |
| 0.31% | `python` | `code_dealloc` | memory |
| 0.31% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.31% | `python` | `initialize_locals` | interpreter |
| 0.30% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `python` | `tuple_traverse` | gc |
| 0.29% | `libc.so.6` | `malloc` | libc |
| 0.29% | `python` | `PyDict_GetItemRef` | dict |
| 0.28% | `python` | `r_long` | import |
| 0.28% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.28% | `[kernel.kallsyms]` | `mas_walk` | kernel |
| 0.27% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.26% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.26% | `[kernel.kallsyms]` | `__count_memcg_events` | kernel |
| 0.25% | `[kernel.kallsyms]` | `memset_orig` | kernel |
| 0.25% | `python` | `_PyTypeCache_Insert` | unknown |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 42.38% | `[JIT]` | `jit` | jit |
| 6.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.85% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.43% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 3.28% | `python` | `PyFloat_FromDouble` | float |
| 2.43% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 2.04% | `python` | `initialize_locals` | interpreter |
| 1.78% | `python` | `_PyObject_Free` | memory |
| 1.51% | `python` | `subtype_dealloc` | memory |
| 1.38% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 1.31% | `python` | `_Py_Dealloc` | memory |
| 1.24% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.19% | `python` | `_PyObject_Malloc` | memory |
| 1.13% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.03% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.99% | `python` | `float_dealloc` | memory |
| 0.92% | `python` | `_Py_NewReference` | memory |
| 0.89% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.77% | `python` | `py_dealloc` | memory |
| 0.74% | `python` | `_PyEval_Vector` | interpreter |
| 0.72% | `python` | `PyType_GenericAlloc` | memory |
| 0.66% | `python` | `PyType_IsSubtype` | dynamic |
| 0.66% | `python` | `PyNumber_Subtract` | dynamic |
| 0.65% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.60% | `python` | `vectorcall_maybe` | unknown |
| 0.60% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.57% | `python` | `float_richcompare` | float |
| 0.53% | `python` | `_PyJIT_Entry` | compiler |
| 0.50% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.49% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.45% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.38% | `python` | `slot_nb_subtract` | unknown |
| 0.38% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.37% | `python` | `PyObject_RichCompare` | dynamic |
| 0.37% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.37% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.35% | `python` | `compactlong_float_guard` | unknown |
| 0.35% | `python` | `tuple_dealloc` | memory |
| 0.34% | `python` | `min_max` | unknown |
| 0.33% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `math.cpython-316-x86_64-linux-gnu.so` | `math_sqrt` | library |
| 0.30% | `python` | `_PyObject_GC_Link` | gc |
| 0.29% | `python` | `float_sub` | float |
| 0.28% | `python` | `PyLong_AsDouble` | int |
| 0.28% | `python` | `tuple_alloc` | memory |
| 0.27% | `python` | `vgetargs1_impl.constprop.0` | calls |
| 0.26% | `python` | `compactlong_float_subtract` | unknown |
| 0.26% | `python` | `_PyCompactLong_Multiply` | unknown |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.78% | `[JIT]` | `jit` | jit |
| 19.64% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.70% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.19% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.37% | `python` | `_PyObject_Free` | memory |
| 1.37% | `python` | `py_dealloc` | memory |
| 1.20% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.06% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.99% | `python` | `_Py_Dealloc` | memory |
| 0.90% | `python` | `bytearray_ass_subscript_lock_held` | miscobj |
| 0.87% | `python` | `tuple_dealloc` | memory |
| 0.86% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.84% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.84% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.82% | `python` | `tuple_alloc` | memory |
| 0.79% | `python` | `PyLong_AsLongAndOverflow` | int |
| 0.74% | `python` | `PyType_IsSubtype` | dynamic |
| 0.73% | `python` | `_PyJIT_Entry` | compiler |
| 0.71% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `PyUnicode_Contains` | str |
| 0.66% | `python` | `set_lookkey` | miscobj |
| 0.64% | `python` | `initialize_locals` | interpreter |
| 0.61% | `python` | `long_richcompare` | int |
| 0.61% | `python` | `_PyLong_FromMedium` | int |
| 0.60% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.59% | `python` | `list_dealloc` | memory |
| 0.55% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.54% | `python` | `PyObject_SetItem` | dynamic |
| 0.54% | `python` | `PyLong_FromSsize_t` | int |
| 0.54% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.51% | `python` | `list_append` | list |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.51% | `python` | `_PyUnicode_Equal` | str |
| 0.51% | `python` | `PyLong_FromLong` | int |
| 0.49% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.47% | `python` | `_PyObject_Realloc` | memory |
| 0.45% | `python` | `min_max` | unknown |
| 0.44% | `python` | `_PyEval_Vector` | interpreter |
| 0.44% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.42% | `python` | `PyList_New.constprop.0` | memory |
| 0.42% | `python` | `make_range_object` | unknown |
| 0.40% | `python` | `_PyCompactLong_Add` | unknown |
| 0.39% | `python` | `_Py_dict_lookup` | lookup |
| 0.38% | `python` | `listiter_next` | list |
| 0.38% | `python` | `_Py_NewReference` | memory |
| 0.37% | `python` | `PySequence_Contains` | dynamic |
| 0.37% | `python` | `PyLong_AsSsize_t` | int |
| 0.36% | `python` | `long_dealloc` | memory |
| 0.32% | `python` | `bytearray_ass_subscript` | miscobj |
| 0.32% | `python` | `_validate_inner` | unknown |
| 0.31% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.30% | `python` | `PyObject_Size` | dynamic |
| 0.28% | `python` | `enum_next` | miscobj |
| 0.28% | `python` | `_PySet_Contains` | miscobj |
| 0.27% | `python` | `PyObject_IsInstance` | dynamic |
| 0.26% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.26% | `python` | `unicodekeys_lookup_unicode` | lookup |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 60.70% | `python` | `sre_ucs1_match` | library |
| 33.73% | `python` | `sre_search` | library |
| 1.19% | `python` | `pattern_subx` | library |
| 0.98% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.63% | `python` | `stringlib_bytes_join_lock_held` | str |
| 0.40% | `python` | `_PyObject_Malloc` | memory |
| 0.30% | `python` | `PyBuffer_Release` | miscobj |
| 0.25% | `python` | `_PyObject_Free` | memory |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 74.70% | `python` | `sre_ucs1_match` | library |
| 16.58% | `python` | `sre_search` | library |
| 3.54% | `python` | `sre_ucs1_count` | library |
| 1.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.43% | `python` | `siphash13` | str |
| 0.30% | `python` | `_PyObject_Malloc` | memory |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 56.87% | `python` | `sre_ucs1_match` | library |
| 5.66% | `python` | `sre_search` | library |
| 4.44% | `python` | `sre_ucs1_count` | library |
| 2.74% | `python` | `pattern_subx` | library |
| 2.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.04% | `python` | `_PyObject_Malloc` | memory |
| 2.03% | `python` | `_PyObject_Free` | memory |
| 1.82% | `python` | `pattern_new_match` | memory |
| 1.78% | `libc.so.6` | `_int_malloc` | libc |
| 1.69% | `[JIT]` | `jit` | jit |
| 1.64% | `python` | `_sre_SRE_Pattern_search` | library |
| 1.14% | `python` | `sre_category` | library |
| 0.97% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.81% | `python` | `_PyUnicode_ToLowercase` | str |
| 0.78% | `python` | `_PyUnicode_IsAlpha` | str |
| 0.66% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.63% | `libc.so.6` | `_int_free_merge_chunk` | libc |
| 0.62% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.49% | `python` | `PyUnicode_Substring` | str |
| 0.46% | `libc.so.6` | `malloc` | libc |
| 0.38% | `python` | `_PyObject_Realloc` | memory |
| 0.37% | `python` | `PyErr_Occurred` | exceptions |
| 0.35% | `libc.so.6` | `_int_free_maybe_consolidate` | libc |
| 0.33% | `python` | `_PyArg_UnpackKeywords` | calls |
| 0.32% | `python` | `_PyUnicode_IsDecimalDigit` | str |
| 0.32% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.31% | `python` | `method_vectorcall_FASTCALL_KEYWORDS_METHOD` | calls |
| 0.31% | `libc.so.6` | `_int_free` | libc |
| 0.29% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.27% | `python` | `_Py_dict_lookup` | lookup |
| 0.27% | `python` | `py_dealloc` | memory |
| 0.27% | `python` | `PyUnicode_New.part.0` | memory |
| 0.27% | `libc.so.6` | `cfree@GLIBC_2.2.5` | libc |
| 0.25% | `libc.so.6` | `unlink_chunk.isra.0` | libc |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 69.68% | `[JIT]` | `jit` | jit |
| 8.90% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.14% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.38% | `python` | `_PyThreadState_PopFrame` | threading |
| 1.66% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.26% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.11% | `python` | `_PyCompactLong_Add` | unknown |
| 1.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.71% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.70% | `python` | `PyObject_IsInstance` | dynamic |
| 0.65% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.49% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.42% | `python` | `long_dealloc` | memory |
| 0.33% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.29% | `python` | `long_div` | int |
| 0.26% | `python` | `_Py_Dealloc` | memory |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 70.62% | `[JIT]` | `jit` | jit |
| 9.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 5.61% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 2.44% | `python` | `_PyThreadState_PopFrame` | threading |
| 2.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.45% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 1.16% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.93% | `python` | `_PyCompactLong_Add` | unknown |
| 0.75% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.60% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.56% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.52% | `python` | `PyObject_IsInstance` | dynamic |
| 0.50% | `python` | `_Py_LoadAttr_StackRefSteal` | unknown |
| 0.32% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.30% | `python` | `long_dealloc` | memory |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.68% | `[JIT]` | `jit` | jit |
| 5.16% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 5.15% | `array.cpython-316-x86_64-linux-gnu.so` | `array_subscr` | library |
| 4.30% | `python` | `PyFloat_FromDouble` | float |
| 3.11% | `python` | `vgetargs1_impl.constprop.0` | calls |
| 2.77% | `python` | `PyObject_GetItem` | dynamic |
| 2.68% | `python` | `convertitem.constprop.0` | unknown |
| 2.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.34% | `python` | `PyLong_AsSsize_t` | int |
| 1.77% | `array.cpython-316-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 1.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.63% | `python` | `PyType_GetModuleByDef` | dynamic |
| 1.57% | `python` | `_PyFloat_ExactDealloc` | memory |
| 1.55% | `python` | `_PyCompactLong_Add` | unknown |
| 1.48% | `python` | `PyIndex_Check` | unknown |
| 1.47% | `python` | `_Py_NewReference` | memory |
| 1.37% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.37% | `python` | `PyArg_Parse` | calls |
| 1.29% | `array.cpython-316-x86_64-linux-gnu.so` | `d_setitem` | library |
| 1.24% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.24% | `array.cpython-316-x86_64-linux-gnu.so` | `d_getitem` | library |
| 1.03% | `python` | `PyLong_FromLong` | int |
| 1.03% | `python` | `float_dealloc` | memory |
| 1.02% | `python` | `_PyCompactLong_Multiply` | unknown |
| 1.02% | `python` | `PyObject_SetItem` | dynamic |
| 0.98% | `python` | `_Py_Dealloc` | memory |
| 0.80% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.79% | `python` | `long_dealloc` | memory |
| 0.64% | `python` | `PyType_IsSubtype` | dynamic |
| 0.56% | `python` | `PyFloat_AsDouble` | float |
| 0.55% | `python` | `_PyLong_FromMedium` | int |
| 0.53% | `python` | `object_isinstance` | dynamic |
| 0.51% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.51% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.47% | `python` | `float_richcompare` | float |
| 0.46% | `array.cpython-316-x86_64-linux-gnu.so` | `PyType_GetModuleByDef@plt` | library |
| 0.45% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.45% | `python` | `tuple_dealloc` | memory |
| 0.44% | `array.cpython-316-x86_64-linux-gnu.so` | `PyIndex_Check@plt` | library |
| 0.43% | `python` | `_PyLong_Frexp` | int |
| 0.43% | `array.cpython-316-x86_64-linux-gnu.so` | `PyNumber_AsSsize_t@plt` | library |
| 0.42% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.40% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.37% | `python` | `tuple_alloc` | memory |
| 0.37% | `python` | `PyObject_IsInstance` | dynamic |
| 0.36% | `python` | `_PyLong_ExactDealloc` | memory |
| 0.32% | `python` | `py_dealloc` | memory |
| 0.30% | `array.cpython-316-x86_64-linux-gnu.so` | `PyFloat_FromDouble@plt` | library |
| 0.29% | `python` | `make_range_object` | unknown |
| 0.28% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.68% | `[JIT]` | `jit` | jit |
| 10.61% | `python` | `_PyCompactLong_Add` | unknown |
| 4.93% | `python` | `long_div` | int |
| 4.29% | `python` | `_PyCompactLong_Multiply` | unknown |
| 4.03% | `python` | `enum_next` | miscobj |
| 3.68% | `python` | `float_compactlong_true_div` | float |
| 2.88% | `python` | `listiter_next` | list |
| 2.76% | `python` | `_PyLong_ExactDealloc` | memory |
| 2.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.33% | `python` | `PyNumber_FloorDivide` | dynamic |
| 1.98% | `python` | `_Py_NewReference` | memory |
| 1.97% | `python` | `PyFloat_FromDouble` | float |
| 1.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.39% | `python` | `_PyLong_FromMedium` | int |
| 1.22% | `python` | `PyLong_FromLong` | int |
| 1.17% | `python` | `PyLong_FromSsize_t` | int |
| 0.93% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.93% | `python` | `nonzero_float_compactlong_guard` | unknown |
| 0.77% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.55% | `python` | `float_dealloc` | memory |
| 0.41% | `python` | `float_compactlong_guard` | float |
| 0.33% | `python` | `_Py_Dealloc` | memory |
| 0.30% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |

## sphinx

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 12.22% | `[JIT]` | `jit` | jit |
| 11.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.35% | `python` | `sre_ucs1_match` | library |
| 3.83% | `python` | `gc_collect_main` | gc |
| 3.74% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.36% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.33% | `python` | `_PyObject_Malloc` | memory |
| 2.13% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.64% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.27% | `python` | `visit_decref` | gc |
| 1.27% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.17% | `python` | `_Py_dict_lookup` | lookup |
| 1.10% | `python` | `initialize_locals` | interpreter |
| 1.07% | `python` | `PyType_IsSubtype` | dynamic |
| 1.02% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.99% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.98% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save_object.constprop.0` | library |
| 0.95% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.81% | `python` | `visit_reachable` | gc |
| 0.74% | `python` | `siphash13` | str |
| 0.71% | `python` | `py_dealloc` | memory |
| 0.63% | `python` | `PyUnicode_Format` | str |
| 0.62% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `sre_search` | library |
| 0.57% | `python` | `_PyJIT_Entry` | compiler |
| 0.49% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.49% | `python` | `PyDict_GetItemRef` | dict |
| 0.48% | `python` | `object_isinstance` | dynamic |
| 0.48% | `python` | `_Py_Dealloc` | memory |
| 0.46% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `save_dict` | library |
| 0.46% | `python` | `tuple_dealloc` | memory |
| 0.45% | `python` | `list_dealloc` | memory |
| 0.44% | `python` | `gen_dealloc` | memory |
| 0.43% | `python` | `sre_ucs2_match` | library |
| 0.42% | `python` | `PyObject_IsInstance` | dynamic |
| 0.42% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.40% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.39% | `python` | `tuple_alloc` | memory |
| 0.38% | `python` | `_PyEval_Vector` | interpreter |
| 0.35% | `python` | `dict_traverse` | gc |
| 0.34% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.32% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 0.32% | `libc.so.6` | `_int_malloc` | libc |
| 0.32% | `python` | `getset_get` | dynamic |
| 0.32% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.30% | `python` | `pattern_subx` | library |
| 0.30% | `python` | `replace` | str |
| 0.30% | `python` | `_PyType_GetDict` | dynamic |
| 0.29% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.29% | `python` | `sre_category` | library |
| 0.28% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `PyObject_SetAttr` | dynamic |
| 0.27% | `python` | `_PyDict_Subscript` | dict |
| 0.26% | `_pickle.cpython-316-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 0.26% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.26% | `python` | `unicode_repr` | str |
| 0.26% | `python` | `sre_ucs1_count` | library |
| 0.26% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |

## sqlalchemy_declarative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.00% | `[JIT]` | `jit` | jit |
| 4.28% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.68% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.45% | `python` | `_PyObject_Malloc` | memory |
| 2.25% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.78% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.67% | `python` | `initialize_locals` | interpreter |
| 1.49% | `python` | `_PyObject_Free` | memory |
| 1.35% | `python` | `tuple_dealloc` | memory |
| 1.27% | `python` | `_Py_dict_lookup` | lookup |
| 1.26% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.16% | `python` | `py_dealloc` | memory |
| 1.15% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.87% | `python` | `PyObject_SetAttr` | dynamic |
| 0.85% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.85% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.78% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.78% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.74% | `python` | `_Py_Dealloc` | memory |
| 0.72% | `python` | `tuple_alloc` | memory |
| 0.70% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.67% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.64% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.57% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.57% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.54% | `python` | `set_lookkey` | miscobj |
| 0.53% | `python` | `PyType_IsSubtype` | dynamic |
| 0.52% | `python` | `dict_dealloc` | memory |
| 0.51% | `python` | `PyObject_IsTrue` | dynamic |
| 0.50% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.50% | `python` | `take_gil` | gil |
| 0.49% | `python` | `subtype_dealloc` | memory |
| 0.49% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.46% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.44% | `python` | `_PyDict_Subscript` | dict |
| 0.43% | `python` | `_PyEval_Vector` | interpreter |
| 0.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.39% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `PyDict_GetItemRef` | dict |
| 0.37% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 0.36% | `python` | `set_dealloc` | memory |
| 0.36% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `list_dealloc` | memory |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.33% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.32% | `python` | `tuple_hash` | tuple |
| 0.31% | `python` | `insertdict` | dict |
| 0.31% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.30% | `python` | `PyObject_Hash` | dynamic |
| 0.28% | `python` | `set_add_entry_takeref` | miscobj |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.25% | `python` | `PyObject_GC_Del` | gc |

## sqlalchemy_imperative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.08% | `[JIT]` | `jit` | jit |
| 4.61% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.09% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 1.98% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.96% | `python` | `_PyObject_Malloc` | memory |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.82% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.58% | `python` | `initialize_locals` | interpreter |
| 1.12% | `python` | `_PyObject_Free` | memory |
| 1.10% | `python` | `tuple_dealloc` | memory |
| 1.10% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.05% | `python` | `_Py_dict_lookup` | lookup |
| 0.88% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 0.86% | `python` | `py_dealloc` | memory |
| 0.79% | `python` | `_Py_Dealloc` | memory |
| 0.71% | `python` | `PyObject_SetAttr` | dynamic |
| 0.70% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.69% | `python` | `tuple_alloc` | memory |
| 0.67% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.63% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.59% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `PyObject_IsTrue` | dynamic |
| 0.54% | `python` | `PyType_IsSubtype` | dynamic |
| 0.52% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.52% | `python` | `gc_collect_main` | gc |
| 0.50% | `python` | `subtype_dealloc` | memory |
| 0.46% | `python` | `dict_dealloc` | memory |
| 0.44% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.42% | `python` | `PyDict_GetItemRef` | dict |
| 0.42% | `python` | `insertdict` | dict |
| 0.41% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.39% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.38% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.38% | `python` | `_PyJIT_Entry` | compiler |
| 0.36% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.34% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.30% | `python` | `long_to_decimal_string_internal` | int |
| 0.30% | `libsqlite3.so.0.8.6` | `sqlite3Parser` | library |
| 0.29% | `python` | `take_gil` | gil |
| 0.28% | `python` | `PyUnicode_Format` | str |
| 0.27% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.27% | `python` | `_PyType_GetDict` | dynamic |
| 0.27% | `python` | `dict_merge` | dict |
| 0.26% | `python` | `insert_to_emptydict` | dict |
| 0.26% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.26% | `python` | `subtype_dict` | unknown |
| 0.26% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 0.25% | `python` | `_PyObject_GC_New` | gc |
| 0.25% | `python` | `PyUnicode_RichCompare` | str |

## sqlglot_v2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.79% | `[JIT]` | `jit` | jit |
| 15.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.72% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.43% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `_PyObject_Free` | memory |
| 2.91% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 2.70% | `python` | `PyType_IsSubtype` | dynamic |
| 2.32% | `python` | `dictiter_iternextitem` | dict |
| 2.13% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.02% | `python` | `py_dealloc` | memory |
| 1.81% | `python` | `PyObject_IsInstance` | dynamic |
| 1.74% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.42% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.30% | `python` | `tuple_dealloc` | memory |
| 1.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 1.14% | `python` | `object_isinstance` | dynamic |
| 1.02% | `python` | `_Py_Dealloc` | memory |
| 0.97% | `python` | `initialize_locals` | interpreter |
| 0.96% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.94% | `python` | `_PyJIT_Entry` | compiler |
| 0.92% | `python` | `_PyObject_GC_New` | gc |
| 0.86% | `python` | `tuple_alloc` | memory |
| 0.85% | `python` | `call_special_method` | unknown |
| 0.76% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.74% | `python` | `gen_dealloc` | memory |
| 0.73% | `python` | `getset_get` | dynamic |
| 0.65% | `python` | `_Py_dict_lookup` | lookup |
| 0.63% | `python` | `insert_to_emptydict` | dict |
| 0.62% | `python` | `PyList_New` | memory |
| 0.62% | `python` | `_PyObject_LookupSpecialMethod` | dynamic |
| 0.61% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.55% | `python` | `_PyObject_Calloc` | memory |
| 0.54% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.52% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.50% | `python` | `method_vectorcall_O` | calls |
| 0.50% | `python` | `_Py_NewReference` | memory |
| 0.46% | `python` | `PyDict_GetItemRef` | dict |
| 0.45% | `python` | `tuple_hash` | tuple |
| 0.42% | `python` | `PyObject_GC_Del` | gc |
| 0.41% | `python` | `func_clear` | unknown |
| 0.40% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.38% | `python` | `object_recursive_isinstance` | dynamic |
| 0.36% | `python` | `dict_get` | dict |
| 0.36% | `python` | `_PyEval_Vector` | interpreter |
| 0.36% | `python` | `PyObject_IsTrue` | dynamic |
| 0.35% | `python` | `dictitems_iter` | unknown |
| 0.32% | `python` | `dict_items` | dict |
| 0.32% | `python` | `_PyObject_GC_Link` | gc |
| 0.32% | `python` | `list_dealloc` | memory |
| 0.32% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.31% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.31% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.31% | `python` | `make_gen` | miscobj |
| 0.30% | `python` | `dictiter_dealloc` | memory |
| 0.29% | `python` | `_PyTuple_FromPairSteal` | tuple |
| 0.28% | `python` | `PyMem_Calloc` | memory |
| 0.26% | `python` | `type___instancecheck__` | dynamic |
| 0.26% | `python` | `set_add_entry_takeref` | miscobj |
| 0.25% | `python` | `dictview_dealloc` | memory |

## sqlglot_v2_optimize

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.65% | `[JIT]` | `jit` | jit |
| 4.55% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.30% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 3.02% | `python` | `PyType_IsSubtype` | dynamic |
| 2.72% | `python` | `_PyObject_Free` | memory |
| 2.72% | `python` | `_PyObject_Malloc` | memory |
| 2.44% | `python` | `dictiter_iternextitem` | dict |
| 1.96% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.80% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.66% | `python` | `py_dealloc` | memory |
| 1.65% | `python` | `PyObject_IsInstance` | dynamic |
| 1.56% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 1.43% | `python` | `tuple_dealloc` | memory |
| 1.22% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.10% | `python` | `object_isinstance` | dynamic |
| 1.10% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.98% | `python` | `call_special_method` | unknown |
| 0.96% | `python` | `tuple_alloc` | memory |
| 0.92% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.92% | `python` | `getset_get` | dynamic |
| 0.91% | `python` | `_Py_Dealloc` | memory |
| 0.88% | `python` | `initialize_locals` | interpreter |
| 0.87% | `python` | `_Py_dict_lookup` | lookup |
| 0.75% | `python` | `_PyObject_LookupSpecialMethod` | dynamic |
| 0.74% | `python` | `_PyObject_RealIsInstance` | dynamic |
| 0.64% | `python` | `_PyObject_Calloc` | memory |
| 0.64% | `python` | `_PyObject_GC_New` | gc |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.57% | `python` | `insert_to_emptydict` | dict |
| 0.57% | `python` | `_PyJIT_Entry` | compiler |
| 0.56% | `python` | `method_vectorcall_O` | calls |
| 0.56% | `python` | `tuple_hash` | tuple |
| 0.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `dict_get` | dict |
| 0.47% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.47% | `python` | `PyObject_IsTrue` | dynamic |
| 0.46% | `python` | `object_recursive_isinstance` | dynamic |
| 0.45% | `python` | `PyList_New` | memory |
| 0.44% | `python` | `_Py_NewReference` | memory |
| 0.44% | `python` | `PyMember_GetOne` | lookup |
| 0.43% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.40% | `python` | `list_dealloc` | memory |
| 0.40% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.40% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.39% | `python` | `PyObject_Hash` | dynamic |
| 0.38% | `python` | `gen_dealloc` | memory |
| 0.38% | `python` | `_PyEval_Vector` | interpreter |
| 0.36% | `python` | `func_clear` | unknown |
| 0.34% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.32% | `python` | `PyMem_Calloc` | memory |
| 0.31% | `python` | `_PyType_GetDict` | dynamic |
| 0.31% | `python` | `siphash13` | str |
| 0.30% | `python` | `PyDict_GetItemRef` | dict |
| 0.30% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `python` | `insertdict` | dict |
| 0.28% | `python` | `object_get_class` | dynamic |
| 0.27% | `python` | `dictiter_dealloc` | memory |
| 0.26% | `python` | `PyList_New.constprop.0` | memory |
| 0.26% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.26% | `python` | `dictitems_iter` | unknown |
| 0.26% | `python` | `dict_items` | dict |
| 0.26% | `python` | `_PyUnicode_JoinArray.part.0` | str |

## sqlglot_v2_parse

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.49% | `[JIT]` | `jit` | jit |
| 14.89% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.36% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.77% | `python` | `initialize_locals` | interpreter |
| 2.42% | `python` | `_PyObject_Malloc` | memory |
| 2.17% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.91% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.80% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.78% | `python` | `_Py_dict_lookup` | lookup |
| 1.55% | `python` | `_PyObject_Free` | memory |
| 1.36% | `python` | `gc_collect_main` | gc |
| 1.16% | `python` | `PyObject_RichCompare` | dynamic |
| 1.01% | `python` | `_PyCompactLong_Add` | unknown |
| 0.90% | `python` | `_PyJIT_Entry` | compiler |
| 0.82% | `python` | `PyType_IsSubtype` | dynamic |
| 0.76% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.76% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.73% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.72% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.70% | `python` | `dictiter_iternextitem` | dict |
| 0.63% | `python` | `dict_get` | dict |
| 0.62% | `python` | `py_dealloc` | memory |
| 0.56% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.54% | `python` | `_Py_Dealloc` | memory |
| 0.53% | `python` | `_PyEval_Vector` | interpreter |
| 0.52% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.51% | `python` | `PyDict_Contains` | dict |
| 0.50% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.42% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.40% | `python` | `clear_slots` | unknown |
| 0.40% | `python` | `insert_to_emptydict` | dict |
| 0.40% | `python` | `PyObject_SetAttr` | dynamic |
| 0.39% | `python` | `visit_decref` | gc |
| 0.36% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.36% | `python` | `object_richcompare` | dynamic |
| 0.35% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.35% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.34% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `set_lookkey` | miscobj |
| 0.32% | `python` | `PyLong_FromSsize_t` | int |
| 0.31% | `python` | `insertdict` | dict |
| 0.31% | `python` | `PyObject_IsTrue` | dynamic |
| 0.30% | `python` | `PyMember_SetOne` | lookup |
| 0.30% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.29% | `python` | `slot_tp_hash` | unknown |
| 0.28% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.28% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.27% | `python` | `subtype_dealloc` | memory |
| 0.27% | `python` | `tuple_dealloc` | memory |
| 0.26% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.25% | `python` | `subtype_traverse` | gc |
| 0.25% | `python` | `PyObject_IsInstance` | dynamic |

## sqlglot_v2_transpile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.72% | `[JIT]` | `jit` | jit |
| 15.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.34% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.78% | `python` | `initialize_locals` | interpreter |
| 2.49% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.41% | `python` | `_PyObject_Malloc` | memory |
| 2.05% | `python` | `_Py_dict_lookup` | lookup |
| 1.75% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.71% | `python` | `_PyObject_Free` | memory |
| 1.52% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.18% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.07% | `python` | `PyObject_RichCompare` | dynamic |
| 1.03% | `python` | `gc_collect_main` | gc |
| 0.99% | `python` | `PyType_IsSubtype` | dynamic |
| 0.95% | `python` | `dict_get` | dict |
| 0.87% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.81% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.80% | `python` | `_PyJIT_Entry` | compiler |
| 0.74% | `python` | `_PyCompactLong_Add` | unknown |
| 0.65% | `python` | `py_dealloc` | memory |
| 0.63% | `python` | `dictiter_iternextitem` | dict |
| 0.62% | `python` | `_Py_Dealloc` | memory |
| 0.58% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.55% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.45% | `python` | `_PyEval_Vector` | interpreter |
| 0.44% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.43% | `python` | `PyDict_Contains` | dict |
| 0.42% | `python` | `PyObject_SetAttr` | dynamic |
| 0.41% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.41% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.40% | `python` | `PyObject_IsTrue` | dynamic |
| 0.39% | `python` | `_PyCompactLong_Subtract` | unknown |
| 0.37% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.37% | `python` | `PyObject_IsInstance` | dynamic |
| 0.36% | `python` | `insert_to_emptydict` | dict |
| 0.35% | `python` | `clear_slots` | unknown |
| 0.35% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 0.35% | `python` | `tuple_dealloc` | memory |
| 0.34% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.33% | `python` | `_PyObject_GC_New` | gc |
| 0.32% | `python` | `visit_decref` | gc |
| 0.32% | `python` | `set_lookkey` | miscobj |
| 0.32% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.30% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.29% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.29% | `python` | `object_richcompare` | dynamic |
| 0.29% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.27% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.26% | `python` | `PyLong_FromSsize_t` | int |
| 0.26% | `python` | `object_isinstance` | dynamic |
| 0.25% | `python` | `dict_dealloc` | memory |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 8.48% | `python` | `take_gil` | gil |
| 6.29% | `libsqlite3.so.0.8.6` | `sqlite3VdbeExec` | library |
| 6.03% | `libc.so.6` | `pthread_mutex_lock@@GLIBC_2.2.5` | libc |
| 4.36% | `libc.so.6` | `pthread_mutex_unlock@@GLIBC_2.2.5` | libc |
| 4.17% | `[JIT]` | `jit` | jit |
| 3.15% | `libm.so.6` | `__cos_fma` | library |
| 2.11% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.99% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 1.82% | `libc.so.6` | `pthread_cond_signal@@GLIBC_2.3.2` | libc |
| 1.77% | `python` | `drop_gil` | gil |
| 1.50% | `python` | `_PyObject_Free` | memory |
| 1.42% | `python` | `_PyObject_Malloc` | memory |
| 1.21% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_fetch_one_row.constprop.0` | library |
| 1.18% | `python` | `_Py_Dealloc` | memory |
| 1.16% | `libsqlite3.so.0.8.6` | `sqlite3BtreeInsert` | library |
| 1.14% | `python` | `_PyThreadState_Attach` | threading |
| 1.07% | `python` | `_PyThreadState_MustExit` | threading |
| 1.07% | `python` | `py_dealloc` | memory |
| 1.03% | `python` | `long_to_decimal_string_internal` | int |
| 0.96% | `python` | `_PyThreadState_Detach` | threading |
| 0.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.93% | `python` | `PyEval_SaveThread` | interpreter |
| 0.74% | `libsqlite3.so.0.8.6` | `sqlite3_step` | library |
| 0.73% | `python` | `tuple_dealloc` | memory |
| 0.70% | `python` | `PyFloat_AsDouble` | float |
| 0.67% | `python` | `PyThread_get_thread_ident` | threading |
| 0.66% | `python` | `_Py_NewReference` | memory |
| 0.65% | `python` | `PyFloat_FromDouble` | float |
| 0.64% | `python` | `_PyLong_FromMedium` | int |
| 0.62% | `libsqlite3.so.0.8.6` | `sqlite3VdbeHalt` | library |
| 0.55% | `python` | `_Py_IsMainThread` | unknown |
| 0.53% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_cursor_init` | library |
| 0.51% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 0.49% | `python` | `PyTuple_New` | memory |
| 0.49% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.48% | `python` | `tuple_alloc` | memory |
| 0.48% | `python` | `PyList_New` | memory |
| 0.48% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `bind_param` | library |
| 0.46% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.45% | `python` | `list_dealloc` | memory |
| 0.45% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.42% | `libsqlite3.so.0.8.6` | `sqlite3BtreeNext` | library |
| 0.41% | `python` | `long_float` | int |
| 0.40% | `python` | `float_dealloc` | memory |
| 0.40% | `libsqlite3.so.0.8.6` | `sqlite3_column_type` | library |
| 0.40% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.39% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.39% | `math.cpython-316-x86_64-linux-gnu.so` | `math_cos` | library |
| 0.38% | `python` | `pthread_mutex_unlock@plt` | unknown |
| 0.38% | `python` | `_Py_dict_lookup` | lookup |
| 0.37% | `python` | `_PyCompactLong_Add` | unknown |
| 0.37% | `libsqlite3.so.0.8.6` | `0x00000000000bd72a` | library |
| 0.37% | `python` | `PyObject_CallObject` | dynamic |
| 0.36% | `python` | `pthread_mutex_lock@plt` | unknown |
| 0.36% | `libsqlite3.so.0.8.6` | `sqlite3BtreeBeginTrans` | library |
| 0.35% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.34% | `python` | `long_dealloc` | memory |
| 0.34% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `_pysqlite_build_py_params` | library |
| 0.32% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.32% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemGrow` | library |
| 0.31% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_connection_execute` | library |
| 0.31% | `python` | `_PyDict_GetItemRef_KnownHash_LockHeld` | dict |
| 0.31% | `python` | `PyObject_Str` | dynamic |
| 0.31% | `python` | `PyType_IsSubtype` | dynamic |
| 0.30% | `libsqlite3.so.0.8.6` | `sqlite3_column_double` | library |
| 0.30% | `python` | `PyList_GetItemRef` | list |
| 0.30% | `python` | `listiter_next` | list |
| 0.29% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.29% | `python` | `initialize_locals` | interpreter |
| 0.28% | `libsqlite3.so.0.8.6` | `sqlite3VdbeMemSetStr` | library |
| 0.28% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.27% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `func_callback` | library |
| 0.27% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.27% | `libsqlite3.so.0.8.6` | `0x00000000000bd749` | library |
| 0.27% | `python` | `PyLong_FromLongLong` | int |
| 0.27% | `python` | `_PyEval_Vector` | interpreter |
| 0.26% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.26% | `_sqlite3.cpython-316-x86_64-linux-gnu.so` | `pysqlite_cursor_iternext` | library |
| 0.26% | `python` | `pthread_cond_signal@plt` | unknown |
| 0.26% | `libsqlite3.so.0.8.6` | `sqlite3_mutex_enter` | library |
| 0.25% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.89% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.14% | `[JIT]` | `jit` | jit |
| 4.59% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.96% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.41% | `python` | `_Py_dict_lookup` | lookup |
| 2.01% | `python` | `_PyObject_Malloc` | memory |
| 2.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.81% | `python` | `initialize_locals` | interpreter |
| 1.48% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.45% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.45% | `python` | `_PyObject_Free` | memory |
| 1.43% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.39% | `python` | `py_dealloc` | memory |
| 1.38% | `python` | `tuple_dealloc` | memory |
| 1.16% | `python` | `PyType_IsSubtype` | dynamic |
| 0.98% | `python` | `tuple_alloc` | memory |
| 0.88% | `python` | `PyDict_GetItemRef` | dict |
| 0.87% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.87% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.85% | `python` | `_Py_Dealloc` | memory |
| 0.82% | `python` | `_PyJIT_Entry` | compiler |
| 0.77% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.70% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.64% | `python` | `insertdict` | dict |
| 0.62% | `python` | `dictiter_iternextitem` | dict |
| 0.61% | `python` | `_PyEval_Vector` | interpreter |
| 0.60% | `python` | `PyUnicode_RichCompare` | str |
| 0.58% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.57% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.57% | `python` | `setiter_iternext` | miscobj |
| 0.57% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.52% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.52% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.48% | `python` | `dict_merge` | dict |
| 0.46% | `python` | `_Py_VectorCallInstrumentation_StackRefSteal` | unknown |
| 0.46% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.46% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.43% | `python` | `slot_tp_richcompare` | dynamic |
| 0.36% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.35% | `python` | `PyObject_IsInstance` | dynamic |
| 0.35% | `python` | `insert_to_emptydict` | dict |
| 0.35% | `python` | `dict_dealloc` | memory |
| 0.34% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.33% | `python` | `PyDict_Next` | dict |
| 0.33% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.33% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 0.33% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.32% | `python` | `PyObject_IsTrue` | dynamic |
| 0.32% | `python` | `_Py_NewReference` | memory |
| 0.31% | `python` | `list_dealloc` | memory |
| 0.31% | `python` | `_PyObject_GC_New` | gc |
| 0.31% | `python` | `PyObject_Hash` | dynamic |
| 0.30% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.29% | `python` | `list_sort_impl` | list |
| 0.29% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.28% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.28% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.27% | `python` | `new_dict.constprop.0` | dict |
| 0.27% | `python` | `method_vectorcall_O` | calls |
| 0.27% | `python` | `PyList_New.constprop.0` | memory |
| 0.27% | `python` | `PyObject_RichCompare` | dynamic |
| 0.26% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.62% | `[JIT]` | `jit` | jit |
| 9.34% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.11% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.98% | `python` | `initialize_locals` | interpreter |
| 2.74% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.21% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.89% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.84% | `python` | `_PyObject_Free` | memory |
| 1.77% | `python` | `_PyObject_Malloc` | memory |
| 1.20% | `python` | `_PyEval_Vector` | interpreter |
| 1.14% | `python` | `long_to_decimal_string_internal` | int |
| 1.10% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.07% | `python` | `_PyCompactLong_Subtract` | unknown |
| 1.07% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.04% | `python` | `PyLong_FromString` | int |
| 1.01% | `python` | `clear_slots` | unknown |
| 0.93% | `python` | `subtype_dealloc` | memory |
| 0.93% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.85% | `python` | `_PyJIT_Entry` | compiler |
| 0.83% | `python` | `_PyCompactLong_Add` | unknown |
| 0.81% | `python` | `_Py_Dealloc` | memory |
| 0.76% | `python` | `py_dealloc` | memory |
| 0.76% | `python` | `_Py_dict_lookup` | lookup |
| 0.69% | `python` | `PyObject_IsTrue` | dynamic |
| 0.68% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.67% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.66% | `python` | `_Py_BuiltinCallFastWithKeywords_StackRef` | unknown |
| 0.59% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.58% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.55% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.53% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.49% | `python` | `PyObject_IsInstance` | dynamic |
| 0.48% | `python` | `slot_nb_bool` | unknown |
| 0.47% | `python` | `min_max` | unknown |
| 0.47% | `python` | `PyLong_FromSsize_t` | int |
| 0.46% | `python` | `tuple_alloc` | memory |
| 0.46% | `python` | `lookup_method_ex.constprop.0` | unknown |
| 0.45% | `libc.so.6` | `_int_malloc` | libc |
| 0.45% | `python` | `PyType_GenericAlloc` | memory |
| 0.43% | `python` | `PyObject_Size` | dynamic |
| 0.43% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `PyObject_Str` | dynamic |
| 0.43% | `python` | `long_pow` | int |
| 0.43% | `python` | `object_isinstance` | dynamic |
| 0.42% | `python` | `PyNumber_Long` | dynamic |
| 0.40% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.40% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.39% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.39% | `python` | `tp_new_wrapper` | memory |
| 0.37% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.36% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.35% | `python` | `sre_ucs1_match` | library |
| 0.34% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.34% | `python` | `tuple_dealloc` | memory |
| 0.33% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.32% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.32% | `python` | `_PyUnicode_Equal` | str |
| 0.30% | `python` | `_Py_NewReference` | memory |
| 0.30% | `python` | `_sre_SRE_Pattern_prefixmatch` | library |
| 0.28% | `python` | `_PyMember_GetOffset` | unknown |
| 0.27% | `python` | `PyUnicode_Concat` | str |
| 0.27% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.27% | `python` | `long_richcompare` | int |
| 0.26% | `python` | `_PyErr_CheckSignalsTstate` | exceptions |
| 0.25% | `python` | `_PyDict_Subscript` | dict |

## thrift

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.27% | `[JIT]` | `jit` | jit |
| 5.71% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.38% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.20% | `python` | `initialize_locals` | interpreter |
| 2.74% | `python` | `_PyObject_Malloc` | memory |
| 2.47% | `python` | `_PyTypeCache_Lookup` | unknown |
| 2.31% | `apache::thrift::py::TType,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*,` | unknown |
| 2.12% | `python` | `_PyObject_Free` | memory |
| 1.77% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.72% | `python` | `insert_to_emptydict` | dict |
| 1.70% | `python` | `_Py_dict_lookup` | lookup |
| 1.56% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.53% | `python` | `py_dealloc` | memory |
| 1.44% | `python` | `PyDict_GetItemRef` | dict |
| 1.30% | `python` | `insertdict` | dict |
| 1.19% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.19% | `python` | `subtype_dealloc` | memory |
| 1.14% | `_object*)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType,` | unknown |
| 1.07% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.03% | `python` | `_Py_Dealloc` | memory |
| 1.00% | `python` | `PyDict_Next` | dict |
| 1.00% | `python` | `PyLong_AsLong` | int |
| 0.99% | `python` | `_PyStack_UnpackDict` | interpreter |
| 0.98% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.88% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.86% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.85% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.84% | `python` | `_PyEval_Vector` | interpreter |
| 0.80% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.80% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.78% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.70% | `python` | `dict_dealloc` | memory |
| 0.68% | `_object*,` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readStruct(_object*,` | unknown |
| 0.66% | `python` | `PyObject_Call` | dynamic |
| 0.65% | `python` | `PyDict_SetItem` | dict |
| 0.63% | `int)` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::readBytes(char**,` | unknown |
| 0.63% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.63% | `python` | `PyUnicode_RichCompare` | str |
| 0.63% | `python` | `PyTuple_Size` | tuple |
| 0.59% | `python` | `PyDict_New` | memory |
| 0.58% | `python` | `unicode_from_format` | str |
| 0.56% | `python` | `_PyDict_FromItems` | dict |
| 0.55% | `python` | `PyType_GenericAlloc` | memory |
| 0.55% | `python` | `tuple_dealloc` | memory |
| 0.51% | `short&)` | `apache::thrift::py::BinaryProtocol::readFieldBegin(apache::thrift::py::TType&,` | unknown |
| 0.51% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.51% | `python` | `PyObject_GetAttr` | dynamic |
| 0.50% | `python` | `vgetargs1_impl` | calls |
| 0.49% | `python` | `_PyObject_VectorcallDictTstate` | dynamic |
| 0.48% | `python` | `find_empty_slot` | dict |
| 0.47% | `python` | `_PyObject_TryGetInstanceAttribute` | dynamic |
| 0.44% | `python` | `find_first_nonascii` | str |
| 0.44% | `python` | `_PyObject_Calloc` | memory |
| 0.44% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.44% | `python` | `_PyDict_Next` | dict |
| 0.43% | `libc.so.6` | `malloc` | libc |
| 0.42% | `_object*)` | `apache::thrift::py::parse_struct_item_spec(apache::thrift::py::StructItemSpec*,` | unknown |
| 0.41% | `python` | `slot_tp_init` | unknown |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.40% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.40% | `python` | `dict_merge` | dict |
| 0.39% | `python` | `_Py_NewReference` | memory |
| 0.39% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.38% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.38% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.37% | `python` | `PyObject_ClearWeakRefs` | dynamic |
| 0.37% | `python` | `type_call` | dynamic |
| 0.35% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 0.35% | `python` | `_PyType_GetDict` | dynamic |
| 0.34% | `fastbinary.cpython-316-x86_64-linux-gnu.so` | `decode_binary` | library |
| 0.34% | `python` | `unicode_fromformat_write_utf8` | str |
| 0.34% | `python` | `PyImport_ImportModuleLevelObject` | import |
| 0.34% | `python` | `_PyObject_Realloc` | memory |
| 0.33% | `python` | `tuple_alloc` | memory |
| 0.32% | `python` | `PyObject_GC_Del` | gc |
| 0.31% | `python` | `_PyUnicode_DecodeUTF8Writer` | str |
| 0.31% | `python` | `PyList_New` | memory |
| 0.30% | `python` | `new_dict.constprop.0` | dict |
| 0.30% | `_object*)` | `apache::thrift::py::parse_struct_args(apache::thrift::py::StructTypeArgs*,` | unknown |
| 0.29% | `python` | `_PyThreadState_PushFrame` | threading |
| 0.29% | `python` | `listiter_next` | list |
| 0.28% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.28% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.28% | `python` | `_PyObject_InitInlineValues` | dynamic |
| 0.27% | `python` | `object_vacall` | dynamic |
| 0.27% | `python` | `PyObject_IsTrue` | dynamic |
| 0.26% | `python` | `_PyObject_GC_Link` | gc |
| 0.26% | `python` | `_Py_module_getattro_impl` | unknown |
| 0.26% | `python` | `_Py_CheckFunctionResult` | calls |
| 0.26% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |

## tomli_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.79% | `[JIT]` | `jit` | jit |
| 7.09% | `python` | `set_lookkey` | miscobj |
| 4.67% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.90% | `python` | `_PyUnicode_Equal` | str |
| 3.85% | `python` | `_PyCompactLong_Add` | unknown |
| 3.30% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.30% | `python` | `_PySet_Contains` | miscobj |
| 2.11% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 1.90% | `python` | `_Py_dict_lookup` | lookup |
| 1.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.66% | `python` | `_PyObject_Malloc` | memory |
| 1.57% | `python` | `_PyLong_ExactDealloc` | memory |
| 1.48% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 1.36% | `python` | `PyObject_Hash` | dynamic |
| 1.18% | `python` | `_PyObject_Free` | memory |
| 0.91% | `[kernel.kallsyms]` | `__irqentry_text_end` | kernel |
| 0.87% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.83% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.83% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.80% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.80% | `python` | `sre_ucs4_match` | library |
| 0.74% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.73% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.73% | `python` | `_Py_NewReference` | memory |
| 0.66% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.59% | `python` | `tuple_alloc` | memory |
| 0.56% | `python` | `_PyDict_Subscript` | dict |
| 0.55% | `python` | `unicode_hash` | str |
| 0.53% | `python` | `py_dealloc` | memory |
| 0.51% | `python` | `_Py_Dealloc` | memory |
| 0.51% | `python` | `replace` | str |
| 0.49% | `python` | `_PyDict_SubscriptKnownHash` | dict |
| 0.45% | `python` | `unicode_decode_utf8_impl` | str |
| 0.45% | `python` | `initialize_locals` | interpreter |
| 0.45% | `[kernel.kallsyms]` | `error_entry` | kernel |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.44% | `python` | `PyDict_Contains` | dict |
| 0.43% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.42% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.41% | `python` | `tuple_dealloc` | memory |
| 0.39% | `python` | `PyDict_GetItemRef` | dict |
| 0.36% | `python` | `siphash13` | str |
| 0.35% | `python` | `memcmp@plt` | unknown |
| 0.34% | `python` | `_PyJIT_Entry` | compiler |
| 0.33% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.31% | `python` | `PyObject_IsInstance` | dynamic |
| 0.29% | `python` | `_PyEval_UnpackIndices` | interpreter |
| 0.28% | `python` | `insertdict` | dict |
| 0.28% | `python` | `make_range_object` | unknown |
| 0.28% | `python` | `object_isinstance` | dynamic |
| 0.28% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.28% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.27% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.26% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.25% | `python` | `PyObject_GetItem` | dynamic |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.66% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.38% | `[JIT]` | `jit` | jit |
| 2.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.90% | `python` | `_PyTypeCache_Lookup` | unknown |
| 1.80% | `python` | `_PyObject_Malloc` | memory |
| 1.66% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 1.22% | `python` | `_PyObject_Free` | memory |
| 1.20% | `python` | `sre_ucs1_match` | library |
| 1.17% | `python` | `initialize_locals` | interpreter |
| 0.89% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.74% | `python` | `_Py_Dealloc` | memory |
| 0.72% | `[kernel.kallsyms]` | `entry_SYSRETQ_unsafe_stack` | kernel |
| 0.70% | `python` | `tuple_dealloc` | memory |
| 0.67% | `[kernel.kallsyms]` | `syscall_return_via_sysret` | kernel |
| 0.65% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.65% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.64% | `python` | `_Py_dict_lookup` | lookup |
| 0.63% | `[nf_tables]` | `nft_do_chain` | unknown |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.57% | `python` | `py_dealloc` | memory |
| 0.54% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.48% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.48% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.46% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 0.45% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.45% | `[kernel.kallsyms]` | `rep_movs_alternative` | kernel |
| 0.43% | `python` | `tuple_alloc` | memory |
| 0.41% | `python` | `PyType_IsSubtype` | dynamic |
| 0.40% | `[kernel.kallsyms]` | `entry_SYSCALL_64_after_hwframe` | kernel |
| 0.40% | `python` | `sre_ucs1_count` | library |
| 0.39% | `python` | `_PyEval_Vector` | interpreter |
| 0.37% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.37% | `python` | `_PyJIT_Entry` | compiler |
| 0.36% | `libc.so.6` | `_int_malloc` | libc |
| 0.28% | `libc.so.6` | `malloc` | libc |
| 0.28% | `[kernel.kallsyms]` | `__tcp_transmit_skb` | kernel |
| 0.28% | `[kernel.kallsyms]` | `entry_SYSCALL_64` | kernel |
| 0.27% | `python` | `_PyTuple_FromStackRefStealOnSuccess` | tuple |
| 0.27% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.26% | `python` | `PyObject_ClearManagedDict` | dynamic |
| 0.26% | `python` | `PyDict_GetItemRef` | dict |
| 0.25% | `python` | `PyObject_IsInstance` | dynamic |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 20.26% | `[JIT]` | `jit` | jit |
| 6.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.92% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.37% | `python` | `_PyObject_Malloc` | memory |
| 2.53% | `python` | `_PyObject_Free` | memory |
| 2.39% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.36% | `python` | `_Py_dict_lookup` | lookup |
| 1.94% | `python` | `py_dealloc` | memory |
| 1.84% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 1.81% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 1.71% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.71% | `python` | `weakref_ref_vectorcall` | miscobj |
| 1.65% | `python` | `_Py_type_getattro_stackref` | unknown |
| 1.64% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 1.63% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.61% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.48% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.38% | `python` | `tuple_dealloc` | memory |
| 1.37% | `python` | `_Py_BuiltinCallFast_StackRef` | unknown |
| 1.17% | `python` | `tuple_alloc` | memory |
| 1.11% | `python` | `set_lookkey` | miscobj |
| 1.00% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.94% | `python` | `getset_get` | dynamic |
| 0.87% | `python` | `_Py_Dealloc` | memory |
| 0.86% | `python` | `initialize_locals` | interpreter |
| 0.85% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.81% | `python` | `_PyObject_GC_New` | gc |
| 0.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.74% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.69% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.66% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.66% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.65% | `python` | `PyArg_UnpackTuple` | calls |
| 0.62% | `python` | `frame_dealloc` | memory |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.58% | `python` | `dict_get` | dict |
| 0.58% | `python` | `PyObject_Hash` | dynamic |
| 0.57% | `python` | `PyType_IsSubtype` | dynamic |
| 0.53% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.52% | `python` | `setiter_iternext` | miscobj |
| 0.52% | `python` | `PyWeakref_NewRef` | memory |
| 0.50% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.45% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.44% | `python` | `wrap_descr_get` | unknown |
| 0.44% | `python` | `PyMapping_Check` | dynamic |
| 0.43% | `python` | `wrapperdescr_call` | unknown |
| 0.43% | `python` | `_Py_type_getattro` | lookup |
| 0.43% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.41% | `python` | `tuple_hash` | tuple |
| 0.40% | `python` | `new_dict.constprop.0` | dict |
| 0.40% | `python` | `_Py_NewReference` | memory |
| 0.39% | `python` | `PyObject_GC_Del` | gc |
| 0.39% | `python` | `PyList_New.constprop.0` | memory |
| 0.38% | `python` | `PyDictProxy_New` | memory |
| 0.38% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.37% | `python` | `_PyObject_GC_Link` | gc |
| 0.37% | `python` | `PyTraceBack_Here` | exceptions |
| 0.36% | `python` | `_PyEval_Vector` | interpreter |
| 0.35% | `python` | `get_exception_handler.isra.0` | unknown |
| 0.35% | `python` | `builtin_getattr` | lookup |
| 0.33% | `python` | `object_richcompare` | dynamic |
| 0.33% | `python` | `wrapper_call` | unknown |
| 0.32% | `python` | `tuple_richcompare` | tuple |
| 0.32% | `python` | `PySequence_Contains` | dynamic |
| 0.31% | `python` | `weakref_hash` | miscobj |
| 0.31% | `python` | `PyDict_Contains` | dict |
| 0.29% | `python` | `mappingproxy_dealloc` | memory |
| 0.29% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 0.29% | `python` | `weakref_richcompare` | miscobj |
| 0.28% | `python` | `_PyJIT_Entry` | compiler |
| 0.28% | `python` | `subtype_dict` | unknown |
| 0.28% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.25% | `python` | `PySet_Contains` | miscobj |

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
| 39.44% | `[JIT]` | `jit` | jit |
| 3.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.37% | `python` | `_Py_dict_lookup` | lookup |
| 3.29% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 3.13% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 3.07% | `python` | `PyObject_IsTrue` | dynamic |
| 2.66% | `python` | `_PyCallMethodDescriptorFast_StackRef` | unknown |
| 2.56% | `python` | `_PyObject_Malloc` | memory |
| 1.89% | `python` | `_io_BytesIO_read` | unknown |
| 1.87% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.78% | `python` | `_PyDict_Subscript` | dict |
| 1.65% | `python` | `_Py_convert_optional_to_ssize_t` | unknown |
| 1.47% | `python` | `bytes_subscript` | str |
| 1.45% | `python` | `_PyObject_Free` | memory |
| 1.20% | `python` | `PyLong_AsSsize_t` | int |
| 1.15% | `python` | `PyUnicode_Decode` | str |
| 1.13% | `python` | `PyBytes_FromStringAndSize` | str |
| 1.11% | `python` | `insertdict` | dict |
| 1.03% | `python` | `PyObject_GetItem` | dynamic |
| 0.97% | `python` | `PyObject_IsInstance` | dynamic |
| 0.89% | `python` | `PyLong_FromSsize_t` | int |
| 0.85% | `python` | `unicode_vectorcall` | str |
| 0.82% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.79% | `python` | `PyObject_Size` | dynamic |
| 0.73% | `python` | `find_first_nonascii` | str |
| 0.62% | `python` | `list_append` | list |
| 0.59% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.59% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.58% | `python` | `list_subscript` | list |
| 0.57% | `python` | `_Py_CallBuiltinClass_StackRef` | unknown |
| 0.54% | `python` | `long_hash` | int |
| 0.49% | `python` | `PyObject_Hash` | dynamic |
| 0.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.46% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.42% | `python` | `object_recursive_isinstance` | dynamic |
| 0.35% | `python` | `_PyDict_SetItem_Take2` | dict |
| 0.32% | `python` | `initialize_locals` | interpreter |
| 0.32% | `python` | `find_empty_slot` | dict |
| 0.32% | `python` | `dictkeys_decref.part.0.constprop.0` | dict |
| 0.31% | `python` | `siphash13` | str |
| 0.31% | `python` | `PyUnicode_New.part.0` | memory |
| 0.31% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.30% | `python` | `_PyObject_Realloc` | memory |
| 0.28% | `python` | `bytes_length` | str |
| 0.28% | `python` | `_Py_Dealloc` | memory |
| 0.28% | `python` | `_PyTypeCache_Lookup` | unknown |
| 0.27% | `python` | `PyUnicode_FromEncodedObject` | str |
| 0.26% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 0.25% | `python` | `PyObject_Malloc` | dynamic |

## xdsl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.80% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 10.30% | `[JIT]` | `jit` | jit |
| 4.32% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.22% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.78% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.77% | `python` | `_PyObject_Free` | memory |
| 1.56% | `python` | `gc_collect_main` | gc |
| 1.53% | `python` | `py_dealloc` | memory |
| 1.41% | `python` | `_Py_dict_lookup` | lookup |
| 1.30% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.14% | `python` | `tuple_dealloc` | memory |
| 1.13% | `python` | `initialize_locals` | interpreter |
| 1.00% | `python` | `PyObject_SetAttr` | dynamic |
| 0.99% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.98% | `python` | `PyDict_GetItemRef` | dict |
| 0.97% | `python` | `_PyType_AllocNoTrack` | memory |
| 0.96% | `python` | `PyObject_GenericSetAttr` | dynamic |
| 0.94% | `python` | `_Py_Dealloc` | memory |
| 0.92% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.86% | `python` | `_PyJIT_Entry` | compiler |
| 0.78% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.78% | `python` | `_Py_VectorCall_StackRefSteal` | unknown |
| 0.73% | `libc.so.6` | `__memset_avx2_unaligned_erms` | libc |
| 0.70% | `python` | `tuple_alloc` | memory |
| 0.69% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.67% | `python` | `unicode_from_format` | str |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `PyTuple_FromArray.part.0` | tuple |
| 0.59% | `python` | `visit_decref` | gc |
| 0.59% | `python` | `_PyEval_Vector` | interpreter |
| 0.58% | `python` | `set_lookkey` | miscobj |
| 0.57% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.55% | `python` | `PyType_IsSubtype` | dynamic |
| 0.53% | `libc.so.6` | `__strchr_avx2` | libc |
| 0.50% | `python` | `visit_reachable` | gc |
| 0.49% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.41% | `python` | `subtype_traverse` | gc |
| 0.40% | `python` | `subtype_dealloc` | memory |
| 0.40% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.36% | `python` | `_abc__abc_instancecheck` | unknown |
| 0.34% | `python` | `dict_traverse` | gc |
| 0.33% | `python` | `PyType_GenericAlloc` | memory |
| 0.33% | `python` | `tuple_iter` | tuple |
| 0.32% | `python` | `_Py_NewReference` | memory |
| 0.32% | `python` | `_PyFunction_Vectorcall` | calls |
| 0.32% | `python` | `_PyUnicode_InternMortal` | str |
| 0.32% | `python` | `_PyThreadState_PopFrame` | threading |
| 0.31% | `python` | `_PyUnicode_ResizeCompact` | str |
| 0.30% | `python` | `PyObject_GetIter` | dynamic |
| 0.30% | `python` | `vgetargskeywords_impl.constprop.0` | unknown |
| 0.30% | `python` | `_Py_type_getattro_stackref` | unknown |
| 0.30% | `python` | `zip_next` | unknown |
| 0.29% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.29% | `python` | `store_instance_attr_lock_held` | unknown |
| 0.28% | `python` | `_Py_type_getattro` | lookup |
| 0.28% | `python` | `PyObject_GC_Del` | gc |
| 0.28% | `python` | `_PyType_GetDict` | dynamic |
| 0.28% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.26% | `python` | `_PyObject_GC_Link` | gc |
| 0.25% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 9.33% | `[JIT]` | `jit` | jit |
| 5.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.37% | `python` | `_PyObject_Malloc` | memory |
| 3.12% | `python` | `_PyTypeCache_Lookup` | unknown |
| 3.07% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 2.96% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 2.80% | `python` | `_PyObject_Free` | memory |
| 2.43% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.82% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.81% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `doContent` | library |
| 1.80% | `python` | `visit_decref` | gc |
| 1.75% | `python` | `gc_collect_main` | gc |
| 1.69% | `python` | `visit_reachable` | gc |
| 1.59% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_update.isra.0` | library |
| 1.49% | `python` | `_Py_dict_lookup` | lookup |
| 1.47% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 1.37% | `python` | `_PyType_LookupStackRefAndVersion` | unknown |
| 1.14% | `python` | `find_first_nonascii` | str |
| 1.03% | `python` | `py_dealloc` | memory |
| 0.92% | `python` | `initialize_locals` | interpreter |
| 0.92% | `python` | `PyUnicode_Contains` | str |
| 0.90% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.90% | `libc.so.6` | `__memmove_avx_unaligned_erms` | libc |
| 0.85% | `python` | `_io_TextIOWrapper_write` | unknown |
| 0.79% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.78% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.78% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `lookupWithLength` | library |
| 0.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.74% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.74% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `sip24_final` | library |
| 0.73% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.73% | `libc.so.6` | `__strlen_avx2` | libc |
| 0.72% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.70% | `python` | `tuple_dealloc` | memory |
| 0.70% | `python` | `_Py_Dealloc` | memory |
| 0.70% | `python` | `siphash13` | str |
| 0.70% | `python` | `_PyObject_GetAttrStackRef` | dynamic |
| 0.68% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.67% | `python` | `getset_get` | dynamic |
| 0.66% | `python` | `PyUnicode_New.part.0` | memory |
| 0.63% | `python` | `_PyObject_GetMethodStackRef` | dynamic |
| 0.63% | `python` | `unicode_decode_utf8.part.0` | str |
| 0.61% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `storeAtts` | library |
| 0.60% | `python` | `PyObject_VectorcallMethod` | dynamic |
| 0.59% | `python` | `_copy_characters.constprop.0.isra.0` | str |
| 0.56% | `python` | `PyDict_GetItemRef` | dict |
| 0.54% | `python` | `_PyEval_Vector` | interpreter |
| 0.46% | `libc.so.6` | `__strncmp_avx2` | libc |
| 0.46% | `python` | `PyList_Append` | list |
| 0.46% | `python` | `list_dealloc` | memory |
| 0.46% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `element_dealloc` | library |
| 0.45% | `python` | `textiowrapper_check_write` | unknown |
| 0.45% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.44% | `python` | `PyType_IsSubtype` | dynamic |
| 0.43% | `python` | `_PyObject_GC_New` | gc |
| 0.41% | `python` | `_PyJIT_Entry` | compiler |
| 0.39% | `python` | `_Py_NewReference` | memory |
| 0.39% | `libc.so.6` | `__memcmp_avx2_movbe` | libc |
| 0.38% | `python` | `_PyType_GetDict` | dynamic |
| 0.38% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_start_handler` | library |
| 0.38% | `python` | `PyObject_GetOptionalAttr` | dynamic |
| 0.38% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.37% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.37% | `python` | `object_isinstance` | dynamic |
| 0.36% | `python` | `long_to_decimal_string_internal` | int |
| 0.36% | `python` | `PyUnicode_Format` | str |
| 0.36% | `pyexpat.cpython-316-x86_64-linux-gnu.so` | `utf8_toUtf8` | library |
| 0.36% | `python` | `PyUnicode_Concat` | str |
| 0.35% | `python` | `unicode_dealloc` | memory |
| 0.33% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `makeuniversal` | library |
| 0.33% | `python` | `_PyTuple_FromPair` | tuple |
| 0.33% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `expat_data_handler` | library |
| 0.32% | `python` | `PyObject_IsInstance` | dynamic |
| 0.32% | `python` | `slot_tp_iternext` | unknown |
| 0.30% | `python` | `_PyObject_GC_Link` | gc |
| 0.30% | `python` | `PyList_New` | memory |
| 0.29% | `python` | `PyObject_IsTrue` | dynamic |
| 0.29% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.29% | `python` | `tuple_alloc` | memory |
| 0.29% | `python` | `PyObject_GC_Del` | gc |
| 0.29% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `treebuilder_extend_element_text_or_tail.isra.0` | library |
| 0.28% | `_elementtree.cpython-316-x86_64-linux-gnu.so` | `create_new_element.isra.0` | library |
| 0.26% | `python` | `bytes_richcompare` | str |
| 0.26% | `python` | `PyObject_CallOneArg` | dynamic |
| 0.26% | `python` | `gen_iternext` | miscobj |
| 0.26% | `python` | `stringlib__two_way` | str |
| 0.25% | `python` | `PyObject_Malloc` | dynamic |
| 0.25% | `python` | `PyBytes_FromStringAndSize` | str |


## Categories

### jit

16.81% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 16.81% | [JIT] | jit |

### memory

12.05% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.16% | python | _PyObject_Malloc |
| 1.72% | python | _PyObject_Free |
| 1.07% | python | py_dealloc |
| 0.75% | python | tuple_dealloc |
| 0.74% | python | _Py_Dealloc |
| 0.72% | python | list_dealloc |
| 0.56% | python | tuple_alloc |
| 0.39% | python | _Py_NewReference |
| 0.29% | python | PyList_New.constprop.0 |
| 0.22% | python | _PyObject_Realloc |
| 0.21% | python | _PyType_AllocNoTrack |
| 0.18% | python | PyTuple_New |
| 0.15% | python | subtype_dealloc |
| 0.14% | python | PyType_GenericAlloc |
| 0.12% | python | gen_dealloc |
| 0.12% | python | PyUnicode_New.part.0 |
| 0.12% | python | dict_dealloc |
| 0.11% | python | unicode_dealloc |
| 0.10% | python | _PyLong_ExactDealloc |
| 0.09% | python | PyCMethod_New |
| 0.09% | python | PyList_New |
| 0.09% | python | long_dealloc |
| 0.09% | python | listiter_dealloc |
| 0.09% | python | zip_new |
| 0.08% | python | PyMethod_New |
| 0.08% | python | _PyObject_Calloc |
| 0.07% | python | PyDict_New |
| 0.07% | python | PySlice_New |
| 0.07% | python | _PyIncrementalNewlineDecoder_decode |
| 0.07% | python | PyUnicode_New |
| 0.06% | python | PyFunction_NewWithQualName |
| 0.06% | python | float_dealloc |
| 0.06% | python | set_dealloc |
| 0.06% | python | _PyFloat_ExactDealloc |
| 0.06% | python | method_dealloc |
| 0.05% | python | pattern_new_match |
| 0.05% | python | long_alloc |
| 0.05% | python | memcpy@plt |
| 0.05% | python | meth_dealloc |
| 0.05% | python | zip_dealloc |
| 0.04% | python | PyMem_Calloc |
| 0.04% | python | PyObject_CallFinalizerFromDealloc |
| 0.04% | python | context_tp_dealloc |
| 0.04% | python | func_dealloc |
| 0.03% | python | PyMem_Free |
| 0.03% | python | allocate_from_new_pool |
| 0.03% | python | slice_dealloc |
| 0.03% | python | memset@plt |
| 0.02% | python | PyMem_Realloc |
| 0.02% | python | frame_dealloc |
| 0.02% | python | tp_new_wrapper |
| 0.02% | python | object_new |
| 0.02% | python | bytes_alloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | object_dealloc |
| 0.02% | python | async_gen_asend_dealloc |
| 0.02% | python | cell_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | range_dealloc |
| 0.01% | python | dictiter_dealloc |
| 0.01% | python | _PyAsyncGenValueWrapperNew |
| 0.01% | python | dictview_dealloc |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | async_gen_wrapped_val_dealloc |
| 0.01% | python | _PyUnicode_ExactDealloc |
| 0.01% | python | match_dealloc |
| 0.01% | python | tb_dealloc |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | unicode_new |
| 0.01% | python | _PyMem_RawMalloc |
| 0.01% | python | PyFunction_New |
| 0.01% | python | slot_tp_new |
| 0.00% | python | code_dealloc |
| 0.00% | python | rangeiter_dealloc |
| 0.00% | python | future_new_iter |
| 0.00% | python | AttributeError_dealloc |
| 0.00% | python | PyWeakref_NewRef |
| 0.00% | python | BaseException_new |
| 0.00% | python | _Py_NewReferenceNoTotal |
| 0.00% | python | TaskStepMethWrapper_dealloc |
| 0.00% | python | PyObject_Realloc |
| 0.00% | python | type_new |
| 0.00% | python | setiter_dealloc |
| 0.00% | python | reversed_new_impl |
| 0.00% | python | _PyMem_RawFree |
| 0.00% | python | TaskObj_dealloc |
| 0.00% | python | structseq_dealloc |

### interpreter

11.03% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 6.71% | python | _PyEval_EvalFrameDefault |
| 1.51% | python | _PyFrame_ClearExceptCode |
| 0.81% | python | initialize_locals |
| 0.68% | python | _PyEval_FrameClearAndPop |
| 0.54% | python | _PyEvalFramePushAndInit |
| 0.31% | python | _PyEval_Vector |
| 0.11% | python | _PyEval_SliceIndex |
| 0.04% | python | call_instrumentation_vector.part.0.isra.0 |
| 0.04% | python | _PyFrame_Traverse |
| 0.03% | python | _PyStack_UnpackDict |
| 0.03% | python | _Py_call_instrumentation_line |
| 0.02% | python | _PyCode_Quicken |
| 0.02% | python | _PyEval_UnpackIndices |
| 0.02% | python | _PyCode_CheckLineNumber |
| 0.02% | python | _PyEval_GetIter |
| 0.01% | python | _PyEvalFramePushAndInit_Ex |
| 0.01% | python | _PyEval_GetAwaitable |
| 0.01% | python | _PyEval_SliceIndexNotNone |
| 0.01% | python | _PyFrame_New_NoTrack |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.01% | python | _PyEval_MonitorRaise |
| 0.01% | python | PyEval_SaveThread |
| 0.01% | python | _PyCode_New |
| 0.00% | python | _PyEval_GetANext |
| 0.00% | python | _PyEval_EnsureBuiltins |
| 0.00% | python | _PyPegen_is_memoized |
| 0.00% | python | PyEval_GetFrame |
| 0.00% | python | _PyEval_ImportName |
| 0.00% | python | _PyEval_CheckExceptTypeValid |
| 0.00% | python | _PyPegen_expect_token |
| 0.00% | python | PyEval_EvalCode |
| 0.00% | python | _PyCode_GetCode |
| 0.00% | python | _PyEval_LoadGlobalStackRef |

### unknown

9.13% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.44% | python | _PyTypeCache_Lookup |
| 0.93% | [unknown] | 0xffffffff939cb32a |
| 0.53% | python | _PyType_LookupStackRefAndVersion |
| 0.50% | python | _PyCompactLong_Add |
| 0.34% | python | _Py_VectorCall_StackRefSteal |
| 0.31% | python | _Py_BuiltinCallFast_StackRef |
| 0.20% | [unknown] | 0xffffffff939cac57 |
| 0.19% | python | _PyCompactLong_Subtract |
| 0.17% | python | zip_next |
| 0.14% | python | _Py_type_getattro_stackref |
| 0.10% | python | _PyCallMethodDescriptorFast_StackRef |
| 0.09% | python | wrapperdescr_call |
| 0.09% | python | _PyRunRemoteDebugger |
| 0.09% | python | slot_mp_ass_subscript |
| 0.09% | python | _Py_bytes_upper |
| 0.09% | python | lookup_method_ex.constprop.0 |
| 0.08% | python | clear_slots |
| 0.08% | python | convertitem.constprop.0 |
| 0.07% | python | _PyForIter_VirtualIteratorNext |
| 0.06% | python | _PyMember_GetOffset |
| 0.06% | python | _PyCompactLong_Multiply |
| 0.06% | python | _PyStaticType_GetState |
| 0.06% | python | make_range_object |
| 0.05% | python | _Py_CallBuiltinClass_StackRef |
| 0.05% | python | _Py_IsMainThread |
| 0.05% | python | func_clear |
| 0.05% | python | _Py_BuiltinCallFastWithKeywords_StackRef |
| 0.05% | python | _Py_BuildMap_StackRefSteal |
| 0.05% | python | PyBytesWriter_Create |
| 0.05% | python | builtin_sum |
| 0.04% | python | _Py_VectorCallInstrumentation_StackRefSteal |
| 0.04% | python | PyIndex_Check |
| 0.04% | python | wrap_objobjargproc |
| 0.04% | python | _PyCallMethodDescriptorFastWithKeywords_StackRef |
| 0.04% | python | sys_audit_tstate |
| 0.04% | python | _Py_BuildString_StackRefSteal |
| 0.03% | python | memcmp@plt |
| 0.03% | python | _PyStolenTuple_Free |
| 0.03% | python | min_max |
| 0.03% | python | store_instance_attr_lock_held |
| 0.03% | python | _PyAsyncGenASend_Send |
| 0.03% | python | PyBytesWriter_FinishWithPointer |
| 0.03% | python | build_indices_generic |
| 0.03% | python | builtin_issubclass |
| 0.03% | python | _PySuper_LookupDescr |
| 0.03% | python | get_exception_handler.isra.0 |
| 0.03% | python | recursive_issubclass |
| 0.03% | python | vgetargskeywords_impl.constprop.0 |
| 0.02% | python | _Py_LoadAttr_StackRefSteal |
| 0.02% | python | slot_tp_init |
| 0.02% | python | _PyInterpreterState_GetConfig |
| 0.02% | python | context_run |
| 0.02% | [unknown] | 0xffffffff93c001c6 |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | TaskStepMethWrapper_call |
| 0.02% | python | Py_HashBuffer |
| 0.02% | python | PySys_Audit |
| 0.02% | python | task_step_impl |
| 0.02% | python | TaskObj_clear |
| 0.02% | python | pthread_self@plt |
| 0.02% | python | _Py_strhex_impl |
| 0.02% | python | call_special_method |
| 0.02% | python | clone_combined_dict_keys |
| 0.02% | python | builtin_id |
| 0.02% | python | gen_finalize |
| 0.02% | python | _PyInterpreterState_Main |
| 0.02% | python | unsafe_long_compare |
| 0.02% | python | builtin_hasattr |
| 0.01% | python | _asyncio_Task___init__ |
| 0.01% | python | maybe_small_long |
| 0.01% | python | _io_TextIOWrapper_write |
| 0.01% | python | PyContext_CopyCurrent |
| 0.01% | [unknown] | 0xffffffff92ce5d2b |
| 0.01% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | supercheck |
| 0.01% | python | tailmatch |
| 0.01% | python | wrapperdescr_get |
| 0.01% | python | future_schedule_callbacks |
| 0.01% | python | vectorcall_maybe |
| 0.01% | python | _PyContext_Exit |
| 0.01% | [unknown] | 0xffffffff93c00151 |
| 0.01% | python | task_wakeup |
| 0.01% | python | bounded_lru_cache_wrapper |
| 0.01% | python | compactlongs_guard |
| 0.01% | python | _Py_bytes_contains |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | python | map_next |
| 0.01% | python | pysiphash |
| 0.01% | python | PyType_GetModule |
| 0.01% | [unknown] | 0xffffffff93c0010f |
| 0.01% | python | _PyFunction_SetVersion |
| 0.01% | python | do_mkvalue |
| 0.01% | python | _PyContext_Enter |
| 0.01% | python | insert_split_key |
| 0.01% | python | builtin_sorted |
| 0.01% | [unknown] | 0xffffffff93c011d3 |
| 0.01% | python | FutureObj_clear |
| 0.01% | [unknown] | 0xffffffff92c57dd9 |
| 0.01% | python | _PyIter_Send |
| 0.01% | python | slot_tp_hash |
| 0.01% | [unknown] | 0xffffffff92c532de |
| 0.01% | python | charmaptranslate_lookup |
| 0.01% | python | slot_sq_contains |
| 0.01% | python | findchar |
| 0.01% | python | any_find_slice |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | dictitems_iter |
| 0.01% | python | make_dict_from_instance_attributes |
| 0.01% | python | malloc@plt |
| 0.01% | python | _asyncio_future_discard_from_awaited_by |
| 0.01% | python | textiowrapper_check_write |
| 0.01% | python | merge_from_seq2_lock_held |
| 0.01% | python | getset_set |
| 0.01% | python | _PyBytes_Concat |
| 0.01% | python | compactlongs_and |
| 0.01% | python | _Py_module_getattro_impl |
| 0.01% | [unknown] | 0xffffffff93c0009d |
| 0.01% | [unknown] | 0xffffffff93c001bd |
| 0.01% | python | binary_op1 |
| 0.01% | python | _PyJIT |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | python | slot_tp_iternext |
| 0.01% | python | _PyOptimizer_Optimize |
| 0.01% | python | task_call_step_soon |
| 0.01% | apache::thrift::py::TType, | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue(_object*, |
| 0.01% | python | strlen@plt |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | python | slot_nb_bool |
| 0.01% | python | _io_BytesIO_read |
| 0.01% | python | _abc__abc_instancecheck |
| 0.01% | python | slot_sq_length |
| 0.01% | python | gallop_right |
| 0.01% | [unknown] | 0xffffffff93c0128c |
| 0.01% | python | mro_implementation_unlocked |
| 0.01% | python | gallop_left |
| 0.01% | python | asciilib_default_find |
| 0.01% | python | func_descr_get |
| 0.01% | python | _Py_slot_tp_getattr_hook |
| 0.01% | python | property_descr_get |
| 0.01% | python | write_bytes_lock_held |
| 0.01% | python | PyTime_AsSecondsDouble |
| 0.01% | python | PyBytesWriter_GetData |
| 0.01% | python | match_getslice_by_index |
| 0.01% | python | slot_sq_item |
| 0.01% | [vdso] | 0x0000000000000b00 |
| 0.00% | python | byteswriter_create |
| 0.00% | python | setitem_take2_lock_held |
| 0.00% | python | listreviter_next |
| 0.00% | python | _PyBytes_Resize |
| 0.00% | [unknown] | 0xffffffff93c01631 |
| 0.00% | python | merge_at |
| 0.00% | python | subtype_clear |
| 0.00% | [unknown] | 0xffffffff92866fc0 |
| 0.00% | python | memmove@plt |
| 0.00% | python | nonzero_float_compactlong_guard |
| 0.00% | python | slot_tp_iter |
| 0.00% | python | _asyncio_Future_add_done_callback |
| 0.00% | python | TaskObj_finalize |
| 0.00% | python | _PyTypeCache_Insert |
| 0.00% | python | _asyncio_future_add_to_awaited_by |
| 0.00% | [unknown] | 0xffffffff93c011a9 |
| 0.00% | [unknown] | 0xffffffff92c57678 |
| 0.00% | python | subtype_dict |
| 0.00% | python | unsafe_object_compare |
| 0.00% | python | member_set |
| 0.00% | [unknown] | 0xffffffff93a44c0e |
| 0.00% | python | compactlong_float_guard |
| 0.00% | python | copy_values |
| 0.00% | python | future_add_done_callback |
| 0.00% | python | _PyJit_translate_single_bytecode_to_trace |
| 0.00% | python | call_soon |
| 0.00% | python | _textiowrapper_writeflush |
| 0.00% | python | va_build_value |
| 0.00% | python | hashtable_unicode_hash |
| 0.00% | python | iter_iternext |
| 0.00% | python | copy_lock_held_untracked |
| 0.00% | python | _Py_bytes_lower |
| 0.00% | python | _PyLexer_get_normal |
| 0.00% | [unknown] | 0xffffffff929df75e |
| 0.00% | python | import_ensure_initialized |
| 0.00% | python | slot_nb_add |
| 0.00% | [unknown] | 0xffffffff936e9148 |
| 0.00% | [unknown] | 0xffffffff929a4ca7 |
| 0.00% | python | future_awaited_by_add.isra.0 |
| 0.00% | python | _Py_BuiltinCallFastWithKeywords_StackRefSteal |
| 0.00% | python | ScandirIterator_iternext |
| 0.00% | python | _asyncio_Future___init__ |
| 0.00% | python | match_getindex |
| 0.00% | python | __errno_location@plt |
| 0.00% | python | int_bit_length |
| 0.00% | [unknown] | 0xffffffff92c54aac |
| 0.00% | [unknown] | 0xffffffff92c54d84 |
| 0.00% | python | _Py_call_instrumentation_arg |
| 0.00% | python | slot_nb_inplace_add |
| 0.00% | python | pthread_mutex_unlock@plt |
| 0.00% | python | _Py_uop_analyze_and_optimize |
| 0.00% | python | _Py_Specialize_Call |
| 0.00% | python | chain_next |
| 0.00% | [unknown] | 0xffffffff936f3c9e |
| 0.00% | python | slot_nb_subtract |
| 0.00% | python | FutureIter_am_send |
| 0.00% | python | strchr@plt |
| 0.00% | [nf_tables] | nft_do_chain |
| 0.00% | _object*) | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue(apache::thrift::py::TType, |
| 0.00% | python | free@plt |
| 0.00% | python | vgetargskeywords.constprop.0 |
| 0.00% | python | builtin_repr |
| 0.00% | [unknown] | 0xffffffff93c01618 |
| 0.00% | python | write_str |
| 0.00% | python | slot_tp_call |
| 0.00% | python | PyBytesWriter_FinishWithSize |
| 0.00% | python | richcmp_eq |
| 0.00% | [unknown] | 0xffffffff93c0125b |
| 0.00% | [unknown] | 0xffffffff92ce5d79 |
| 0.00% | python | _PyFunction_FromConstructor |
| 0.00% | [unknown] | 0xffffffff92c25c73 |
| 0.00% | python | _asyncio_current_task |
| 0.00% | python | asciilib_fastsearch.constprop.1 |
| 0.00% | python | PyBytesWriter_Finish |
| 0.00% | python | wrapper_call |
| 0.00% | python | _pystat_fromstructstat |
| 0.00% | python | gen_close |
| 0.00% | python | analyze_descriptor_load.constprop.0 |
| 0.00% | python | PyCallable_Check |
| 0.00% | python | do_raise |
| 0.00% | python | slot_mp_subscript |
| 0.00% | python | memchr@plt |
| 0.00% | python | task_step |
| 0.00% | [unknown] | 0xffffffff939cb1a6 |
| 0.00% | python | _Py_call_instrumentation |
| 0.00% | python | compactlong_float_subtract |
| 0.00% | [unknown] | 0xffffffff936f5163 |
| 0.00% | python | partial_vectorcall |
| 0.00% | [kvm] | pvclock_gtod_notify |

### library

8.40% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.76% | python | sre_ucs1_match |
| 0.43% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base85 |
| 0.30% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base64 |
| 0.30% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_ascii85 |
| 0.27% | python | sre_search |
| 0.27% | _pickle.cpython-315-x86_64-linux-gnu.so | save.constprop.0 |
| 0.26% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base64 |
| 0.22% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_hex_impl.isra.0 |
| 0.21% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_a2b_base32 |
| 0.15% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base32 |
| 0.14% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_base85 |
| 0.12% | _json.cpython-316-x86_64-linux-gnu.so | scanstring_unicode |
| 0.12% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write |
| 0.12% | array.cpython-316-x86_64-linux-gnu.so | array_subscr |
| 0.11% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_b2a_ascii85 |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_dict |
| 0.11% | _pickle.cpython-315-x86_64-linux-gnu.so | save_long |
| 0.10% | _pickle.cpython-315-x86_64-linux-gnu.so | load |
| 0.09% | python | sre_ucs1_count |
| 0.07% | _pickle.cpython-315-x86_64-linux-gnu.so | save_list |
| 0.07% | _pickle.cpython-315-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.07% | libz.so.1.3 | 0x0000000000008c1c |
| 0.06% | python | _sre_SRE_Pattern_prefixmatch |
| 0.06% | _pickle.cpython-315-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.06% | libz.so.1.3 | 0x0000000000008c20 |
| 0.06% | _json.cpython-316-x86_64-linux-gnu.so | scan_once_unicode |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_contentTok |
| 0.05% | libz.so.1.3 | 0x0000000000002dda |
| 0.05% | libz.so.1.3 | 0x0000000000002dce |
| 0.05% | libz.so.1.3 | 0x0000000000008bf7 |
| 0.05% | libz.so.1.3 | 0x0000000000002de6 |
| 0.05% | libz.so.1.3 | 0x0000000000002dd1 |
| 0.05% | libz.so.1.3 | 0x0000000000002dd6 |
| 0.05% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_updatePosition |
| 0.05% | libz.so.1.3 | 0x0000000000002dc3 |
| 0.04% | array.cpython-316-x86_64-linux-gnu.so | array_ass_subscr |
| 0.04% | _math_integer.cpython-316-x86_64-linux-gnu.so | factorial_partial_product |
| 0.04% | python | sre_ucs4_match |
| 0.04% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_trace |
| 0.03% | _heapq.cpython-316-x86_64-linux-gnu.so | siftup |
| 0.03% | python | pattern_subx |
| 0.03% | libz.so.1.3 | 0x0000000000008192 |
| 0.03% | libz.so.1.3 | 0x0000000000008be6 |
| 0.03% | libz.so.1.3 | 0x00000000000082aa |
| 0.03% | array.cpython-316-x86_64-linux-gnu.so | d_setitem |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | doContent |
| 0.03% | libz.so.1.3 | 0x0000000000008c25 |
| 0.03% | array.cpython-316-x86_64-linux-gnu.so | d_getitem |
| 0.03% | libsqlite3.so.0.8.6 | sqlite3VdbeExec |
| 0.03% | libz.so.1.3 | 0x0000000000008bed |
| 0.03% | python | sre_category |
| 0.03% | libz.so.1.3 | 0x0000000000008c2c |
| 0.03% | libz.so.1.3 | 0x0000000000008bd6 |
| 0.03% | _pickle.cpython-316-x86_64-linux-gnu.so | save_object.constprop.0 |
| 0.03% | libz.so.1.3 | 0x0000000000008c07 |
| 0.03% | libz.so.1.3 | 0x0000000000008c18 |
| 0.03% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_put |
| 0.03% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_update.isra.0 |
| 0.02% | libm.so.6 | __ieee754_pow_fma |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | save_unicode |
| 0.02% | libz.so.1.3 | 0x00000000000082b7 |
| 0.02% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_nameLength |
| 0.02% | libz.so.1.3 | 0x000000000000819f |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pickler_clear |
| 0.02% | libm.so.6 | __cos_fma |
| 0.02% | _json.cpython-316-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.02% | libz.so.1.3 | 0x0000000000008bdf |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.02% | libz.so.1.3 | 0x0000000000008c2f |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | Pdata_push |
| 0.02% | python | _sre_SRE_Pattern_search |
| 0.02% | libz.so.1.3 | 0x0000000000008bf1 |
| 0.02% | libz.so.1.3 | 0x0000000000008c0a |
| 0.02% | libz.so.1.3 | 0x0000000000008bfa |
| 0.02% | _pickle.cpython-315-x86_64-linux-gnu.so | do_append |
| 0.02% | python | sre_ucs2_match |
| 0.02% | libz.so.1.3 | 0x0000000000008c01 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | libz.so.1.3 | 0x0000000000008c0e |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | ascii_escape_size |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_gc_traverse |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | save_dict |
| 0.01% | libz.so.1.3 | 0x0000000000008bd0 |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | lookupWithLength |
| 0.01% | libz.so.1.3 | 0x0000000000008267 |
| 0.01% | libz.so.1.3 | 0x0000000000008172 |
| 0.01% | libz.so.1.3 | 0x0000000000008258 |
| 0.01% | libz.so.1.3 | 0x000000000000828a |
| 0.01% | libz.so.1.3 | 0x0000000000008c2a |
| 0.01% | libz.so.1.3 | 0x0000000000008140 |
| 0.01% | libz.so.1.3 | 0x000000000000814f |
| 0.01% | libz.so.1.3 | 0x0000000000008161 |
| 0.01% | libz.so.1.3 | 0x0000000000008c14 |
| 0.01% | libz.so.1.3 | 0x0000000000008182 |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | sip24_final |
| 0.01% | libz.so.1.3 | 0x000000000000829a |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | libz.so.1.3 | 0x0000000000008279 |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | libm.so.6 | __sin_fma |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | do_setitems |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyType_GetModuleByDef@plt |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyIndex_Check@plt |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | write_escaped_ascii |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyNumber_AsSsize_t@plt |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | storeAtts |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.01% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | memo_get |
| 0.01% | _heapq.cpython-316-x86_64-linux-gnu.so | siftdown |
| 0.01% | libz.so.1.3 | inflate |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | Unpickler_clear |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_dealloc |
| 0.01% | binascii.cpython-316-x86_64-linux-gnu.so | ascii_buffer_converter |
| 0.01% | _json.cpython-316-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_clear |
| 0.01% | libz.so.1.3 | 0x0000000000002419 |
| 0.01% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_AsLongAndOverflow@plt |
| 0.01% | array.cpython-316-x86_64-linux-gnu.so | PyFloat_FromDouble@plt |
| 0.01% | libz.so.1.3 | 0x000000000000242e |
| 0.01% | libz.so.1.3 | 0x0000000000002416 |
| 0.01% | libz.so.1.3 | 0x0000000000008be3 |
| 0.01% | libz.so.1.3 | 0x0000000000008196 |
| 0.01% | libz.so.1.3 | 0x0000000000008c37 |
| 0.01% | ld-linux-x86-64.so.2 | _dl_relocate_object |
| 0.01% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_factorial |
| 0.01% | libz.so.1.3 | 0x0000000000008c28 |
| 0.01% | libz.so.1.3 | 0x00000000000023f4 |
| 0.01% | libz.so.1.3 | 0x00000000000082ae |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_start_handler |
| 0.01% | libz.so.1.3 | 0x0000000000008bfe |
| 0.01% | pyexpat.cpython-316-x86_64-linux-gnu.so | utf8_toUtf8 |
| 0.01% | _random.cpython-316-x86_64-linux-gnu.so | genrand_uint32 |
| 0.01% | libssl.so.3 | 0x0000000000055398 |
| 0.01% | math.cpython-316-x86_64-linux-gnu.so | math_sqrt |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | makeuniversal |
| 0.01% | python | sre_ucs4_count |
| 0.01% | _elementtree.cpython-316-x86_64-linux-gnu.so | expat_data_handler |
| 0.01% | _sqlite3.cpython-316-x86_64-linux-gnu.so | _pysqlite_fetch_one_row.constprop.0 |
| 0.01% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write |
| 0.00% | _math_integer.cpython-316-x86_64-linux-gnu.so | math_integer_gcd |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyDict_Next@plt |
| 0.00% | libz.so.1.3 | 0x0000000000002403 |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3BtreeInsert |
| 0.00% | libz.so.1.3 | 0x000000000000829e |
| 0.00% | libz.so.1.3 | 0x000000000000828e |
| 0.00% | libz.so.1.3 | 0x000000000000827d |
| 0.00% | ld-linux-x86-64.so.2 | do_lookup_x |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | marker |
| 0.00% | libz.so.1.3 | 0x000000000000826c |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | treebuilder_extend_element_text_or_tail.isra.0 |
| 0.00% | libz.so.1.3 | 0x00000000000082bb |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | create_new_element.isra.0 |
| 0.00% | _random.cpython-316-x86_64-linux-gnu.so | _random_Random_getrandbits |
| 0.00% | tracer.cpython-316-x86_64-linux-gnu.so | CTracer_set_pdata_stack.constprop.0 |
| 0.00% | libz.so.1.3 | 0x0000000000008144 |
| 0.00% | libz.so.1.3 | 0x000000000000825c |
| 0.00% | python | _sre_SRE_Match_group |
| 0.00% | libz.so.1.3 | 0x00000000000081a3 |
| 0.00% | libz.so.1.3 | 0x0000000000008154 |
| 0.00% | unicodedata.cpython-316-x86_64-linux-gnu.so | unicodedata_UCD_combining |
| 0.00% | libz.so.1.3 | 0x0000000000008176 |
| 0.00% | python | _sre_SRE_Pattern_sub |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_IsTrue@plt |
| 0.00% | array.cpython-316-x86_64-linux-gnu.so | i_getitem |
| 0.00% | libz.so.1.3 | 0x0000000000008165 |
| 0.00% | libz.so.1.3 | 0x0000000000008186 |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | memo_get |
| 0.00% | python | sys_trace_start |
| 0.00% | _ssl.cpython-315-x86_64-linux-gnu.so | _ssl__SSLSocket_read |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | Pickler_traverse |
| 0.00% | python | _sre_SRE_Match_end |
| 0.00% | libz.so.1.3 | 0x00000000000023f0 |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | xmlparser_append_event.isra.0 |
| 0.00% | python | sys_trace_return |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_resize |
| 0.00% | array.cpython-316-x86_64-linux-gnu.so | PyArg_Parse@plt |
| 0.00% | _heapq.cpython-316-x86_64-linux-gnu.so | _heapq_heappush |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyObject_GetBuffer@plt |
| 0.00% | libsqlite3.so.0.8.6 | sqlite3VdbeHalt |
| 0.00% | _elementtree.cpython-316-x86_64-linux-gnu.so | element_getitem |
| 0.00% | _heapq.cpython-316-x86_64-linux-gnu.so | _heapq_heappop |
| 0.00% | _struct.cpython-316-x86_64-linux-gnu.so | pack |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | PyLong_FromLong@plt |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | PyBuffer_Release@plt |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_MemoGet |
| 0.00% | _pickle.cpython-316-x86_64-linux-gnu.so | _Pickler_Write.constprop.0 |
| 0.00% | libz.so.1.3 | 0x000000000000381f |
| 0.00% | ld-linux-x86-64.so.2 | strcmp |
| 0.00% | _json.cpython-316-x86_64-linux-gnu.so | encoder_write_string |
| 0.00% | unicodedata.cpython-316-x86_64-linux-gnu.so | unicodedata_UCD_east_asian_width |
| 0.00% | python | _sre_SRE_Match_groupdict |
| 0.00% | libz.so.1.3 | 0x0000000000002412 |
| 0.00% | libm.so.6 | pow@@GLIBC_2.29 |
| 0.00% | _pickle.cpython-315-x86_64-linux-gnu.so | _Unpickler_New |
| 0.00% | libm.so.6 | __wrap_scalbn |
| 0.00% | _struct.cpython-316-x86_64-linux-gnu.so | s_pack_internal |
| 0.00% | binascii.cpython-316-x86_64-linux-gnu.so | binascii_unhexlify |

### gc

7.17% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.78% | python | gc_collect_main |
| 1.50% | python | visit_reachable |
| 1.43% | python | visit_decref |
| 0.57% | python | PyObject_GC_UnTrack |
| 0.33% | python | list_traverse |
| 0.25% | python | dict_traverse |
| 0.23% | python | subtype_traverse |
| 0.17% | python | _PyObject_GC_New |
| 0.15% | python | PyObject_GC_Del |
| 0.11% | python | _PyObject_GC_Link |
| 0.10% | python | _PyObject_GC_NewVar |
| 0.07% | python | _PyGC_VisitFrameStack |
| 0.06% | python | tuple_traverse |
| 0.05% | python | func_traverse |
| 0.05% | python | TaskObj_traverse |
| 0.04% | python | gen_traverse |
| 0.04% | python | set_traverse |
| 0.03% | python | _PyTuple_MaybeUntrack |
| 0.03% | python | type_is_gc |
| 0.02% | python | context_tp_traverse |
| 0.02% | python | type_traverse |
| 0.02% | python | PyObject_GC_Track |
| 0.02% | python | meth_traverse |
| 0.01% | python | FutureObj_traverse |
| 0.01% | python | PyObject_IS_GC |
| 0.01% | python | _PyGC_VisitStackRef |
| 0.01% | python | TaskStepMethWrapper_traverse |
| 0.01% | python | method_traverse |
| 0.01% | python | FutureIter_traverse |
| 0.00% | python | gc_traverse |
| 0.00% | python | cell_traverse |
| 0.00% | python | descr_traverse |
| 0.00% | python | module_traverse |
| 0.00% | python | visit_add_to_container |

### dynamic

6.44% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.73% | python | PyObject_RichCompareBool |
| 0.61% | python | _PyObject_GenericGetAttrWithDict |
| 0.34% | python | PyType_IsSubtype |
| 0.28% | python | _PyObject_GetAttrStackRef |
| 0.26% | python | PyObject_Hash |
| 0.23% | python | _PyObject_MakeTpCall |
| 0.18% | python | PyObject_GetOptionalAttr |
| 0.18% | python | PyNumber_AsSsize_t |
| 0.17% | python | PyObject_Vectorcall |
| 0.15% | python | _PyObject_TryGetInstanceAttribute |
| 0.14% | python | _PyObject_GetMethodStackRef |
| 0.14% | python | PyObject_IsInstance |
| 0.13% | python | _PyType_GetDict |
| 0.12% | python | PyObject_IsTrue |
| 0.11% | python | PyObject_RichCompare |
| 0.11% | python | PyObject_GetItem |
| 0.10% | python | object_isinstance |
| 0.09% | python | PyObject_Malloc |
| 0.09% | python | PyObject_SetItem |
| 0.09% | python | PyObject_Size |
| 0.09% | python | getset_get |
| 0.09% | python | PyObject_GetIter |
| 0.08% | python | PyObject_IsSubclass |
| 0.08% | python | PyObject_SetAttr |
| 0.08% | python | PyObject_VisitManagedDict |
| 0.08% | python | PyObject_CallOneArg |
| 0.08% | python | PyObject_ClearManagedDict |
| 0.07% | python | PyObject_Free |
| 0.07% | python | type_call |
| 0.07% | python | PyType_GetModuleByDef |
| 0.07% | python | PyObject_GenericSetAttr |
| 0.06% | python | slot_tp_richcompare |
| 0.05% | python | PyObject_Call |
| 0.05% | python | _PyObject_VectorcallPrepend |
| 0.05% | python | PyNumber_Remainder |
| 0.05% | python | PySequence_Fast |
| 0.04% | python | _PyObject_RealIsSubclass |
| 0.04% | python | PyObject_ClearWeakRefs |
| 0.04% | python | PyObject_Str |
| 0.04% | python | PyObject_VectorcallMethod |
| 0.04% | python | PyDescr_IsData |
| 0.03% | python | method_get |
| 0.03% | python | PyObject_GetBuffer |
| 0.03% | python | PyObject_Repr |
| 0.03% | python | PyObject_GetAttr |
| 0.03% | python | _PyObject_LookupSpecial |
| 0.03% | python | PyObject_DelItem |
| 0.03% | python | PyIter_Next |
| 0.03% | python | _PyObject_VectorcallDictTstate |
| 0.03% | python | delitem_common |
| 0.03% | python | PySequence_Contains |
| 0.02% | python | PyNumber_Multiply |
| 0.02% | python | _PyObject_InitInlineValues |
| 0.02% | python | PyIter_Send |
| 0.02% | python | PyNumber_Add |
| 0.02% | python | object_recursive_isinstance |
| 0.02% | python | PyNumber_FloorDivide |
| 0.02% | python | type_ready |
| 0.02% | python | object_get_class |
| 0.02% | python | object_init |
| 0.02% | python | _PyObject_Call_Prepend |
| 0.02% | python | _PyNumber_Index |
| 0.02% | python | PyNumber_Index |
| 0.02% | python | _PyObject_LookupSpecialMethod |
| 0.02% | python | object_richcompare |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | _PySuper_Lookup |
| 0.01% | python | _PyObject_StoreInstanceAttribute |
| 0.01% | python | PyObject_GenericGetAttr |
| 0.01% | python | PyObject_GenericHash |
| 0.01% | python | PyNumber_Negative |
| 0.01% | python | PyNumber_InPlaceAdd |
| 0.01% | python | PyNumber_Rshift |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | PyNumber_Lshift |
| 0.01% | python | _Py_type_getattro_impl |
| 0.01% | python | _PyObject_RealIsInstance |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | PyNumber_Subtract |
| 0.01% | python | type_name |
| 0.01% | python | PyNumber_Xor |
| 0.01% | python | object___reduce_ex__ |
| 0.01% | python | PySequence_GetItem |
| 0.01% | python | PyNumber_Long |
| 0.01% | python | PySequence_Tuple |
| 0.00% | python | PyObject_GenericGetDict |
| 0.00% | python | PySequence_List |
| 0.00% | python | PyNumber_TrueDivide |
| 0.00% | python | _PyNumber_PowerNoMod |
| 0.00% | python | _PyObject_SetAttributeErrorContext |
| 0.00% | python | PyNumber_InPlaceOr |
| 0.00% | python | type___instancecheck__ |
| 0.00% | python | PyObject_HasAttrWithError |
| 0.00% | python | object_vacall |
| 0.00% | python | _PyObject_CallFunctionVa |
| 0.00% | python | PyObject_SetAttrString |
| 0.00% | python | _PyObject_ClearFreeLists |
| 0.00% | python | PyObject_SelfIter |
| 0.00% | python | PyNumber_Float |
| 0.00% | python | PyIter_Check |
| 0.00% | python | PyNumber_And |

### lookup

5.26% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 3.11% | python | unicodekeys_lookup_unicode |
| 1.97% | python | _Py_dict_lookup |
| 0.04% | python | find_name_in_mro |
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

4.94% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.80% | libc.so.6 | __memmove_avx_unaligned_erms |
| 0.55% | libc.so.6 | __memset_avx2_unaligned_erms |
| 0.34% | libc.so.6 | __memcmp_avx2_movbe |
| 0.18% | libc.so.6 | _int_malloc |
| 0.08% | libc.so.6 | malloc |
| 0.06% | libc.so.6 | __strlen_avx2 |
| 0.05% | libc.so.6 | _int_free_merge_chunk |
| 0.04% | libc.so.6 | _int_free |
| 0.04% | libc.so.6 | __memchr_avx2 |
| 0.04% | libc.so.6 | unlink_chunk.isra.0 |
| 0.04% | libc.so.6 | cfree@GLIBC_2.2.5 |
| 0.04% | libc.so.6 | pthread_mutex_lock@@GLIBC_2.2.5 |
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
| 0.02% | libcrypto.so.3 | 0x00000000002dcc92 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbae |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb95 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8cf |
| 0.01% | libcrypto.so.3 | 0x00000000002dcabc |
| 0.01% | libcrypto.so.3 | 0x00000000002dc8da |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd13 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcac7 |
| 0.01% | libcrypto.so.3 | 0x00000000002dc9e6 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba4 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcd01 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccd2 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc6a |
| 0.01% | libcrypto.so.3 | 0x00000000002dcba9 |
| 0.01% | libcrypto.so.3 | 0x00000000002dccee |
| 0.01% | libc.so.6 | realloc |
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
| 0.01% | libc.so.6 | pthread_cond_signal@@GLIBC_2.3.2 |
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
| 0.01% | libc.so.6 | _int_realloc |
| 0.01% | libcrypto.so.3 | OPENSSL_cleanse |
| 0.01% | libcrypto.so.3 | 0x00000000002dcc60 |
| 0.01% | libcrypto.so.3 | OSSL_PARAM_locate |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb49 |
| 0.01% | libcrypto.so.3 | BIO_ctrl |
| 0.01% | libc.so.6 | pthread_rwlock_unlock@@GLIBC_2.34 |
| 0.01% | libc.so.6 | __strncmp_avx2 |
| 0.01% | libc.so.6 | pthread_rwlock_rdlock@GLIBC_2.2.5 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbbd |
| 0.01% | libc.so.6 | clock_gettime@@GLIBC_2.17 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb58 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcbb3 |
| 0.01% | libcrypto.so.3 | 0x00000000002dcb67 |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_ctrl |
| 0.01% | libc.so.6 | __errno_location |
| 0.01% | libcrypto.so.3 | EVP_CIPHER_CTX_get_iv_length |
| 0.01% | libc.so.6 | __memrchr_avx2 |
| 0.01% | libcrypto.so.3 | 0x00000000000c0ddb |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb53 |
| 0.00% | libc.so.6 | __printf_buffer |
| 0.00% | libcrypto.so.3 | 0x00000000002dcd0a |
| 0.00% | libc.so.6 | malloc_consolidate |
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
| 0.00% | libcrypto.so.3 | 0x00000000002dcb36 |
| 0.00% | libc.so.6 | __gconv_transform_utf8_internal |
| 0.00% | libc.so.6 | __GI___readdir64 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcc65 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcb85 |
| 0.00% | libcrypto.so.3 | 0x00000000002dcca6 |

### dict

3.47% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.62% | python | _PyDict_Subscript |
| 0.52% | python | dictiter_iternextkey |
| 0.35% | python | insertdict |
| 0.29% | python | PyDict_GetItemRef |
| 0.17% | python | dictkeys_decref.part.0.constprop.0 |
| 0.17% | python | build_indices_unicode |
| 0.16% | python | PyDict_Next |
| 0.11% | python | insert_to_emptydict |
| 0.09% | python | dict_get |
| 0.09% | python | find_empty_slot |
| 0.08% | python | PyDict_Contains |
| 0.08% | python | dictiter_iternextitem |
| 0.07% | python | _PyDict_SetItem_Take2 |
| 0.06% | python | _PyDict_FromItems |
| 0.06% | python | new_dict.constprop.0 |
| 0.05% | python | _PyDict_StoreSubscript |
| 0.05% | python | dict_setdefault_ref_lock_held |
| 0.05% | python | _PyDict_LoadBuiltinsFromGlobals |
| 0.05% | python | _PyDict_Next |
| 0.05% | python | dict_merge |
| 0.04% | python | _PyDict_SubscriptKnownHash |
| 0.03% | python | dictresize |
| 0.03% | python | new_keys_object |
| 0.02% | python | insertdict.isra.0 |
| 0.02% | python | dictiter_iternextvalue |
| 0.02% | python | PyDict_SetItem |
| 0.01% | python | dict_items |
| 0.01% | python | PyDict_GetItem |
| 0.01% | python | find_empty_slot.constprop.0 |
| 0.01% | python | _PyDict_DelItem_KnownHash_LockHeld |
| 0.01% | python | dict_ass_sub |
| 0.01% | python | _PyDict_MergeUniq |
| 0.01% | python | dict_pop |
| 0.01% | python | _PyDict_LoadGlobalStackRef |
| 0.01% | python | _PyDict_GetItemRef_KnownHash_LockHeld |
| 0.01% | python | dict_iter |
| 0.01% | python | _PyDict_GetMethodStackRef |
| 0.01% | python | new_dict |
| 0.00% | python | PyDict_GetItemWithError |
| 0.00% | python | dict_vectorcall |
| 0.00% | python | dict_update |
| 0.00% | python | insert_to_emptydict.isra.0 |
| 0.00% | python | dict___contains__ |

### miscobj

2.55% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.07% | python | set_lookkey |
| 0.45% | python | PySlice_AdjustIndices |
| 0.17% | python | _PySet_Contains |
| 0.10% | python | PySlice_Unpack |
| 0.07% | python | gen_iternext |
| 0.07% | python | make_gen |
| 0.06% | python | set_add_entry_takeref |
| 0.05% | python | PyBool_FromLong |
| 0.05% | python | setiter_iternext |
| 0.05% | python | PyBuffer_Release |
| 0.04% | python | PyBuffer_FillInfo |
| 0.04% | python | enum_next |
| 0.03% | python | range_iter |
| 0.03% | python | set_issubset_impl |
| 0.03% | python | _PyBuildSlice_ConsumeRefs |
| 0.03% | python | deque_append |
| 0.02% | python | set_table_resize |
| 0.02% | python | deque_popleft |
| 0.02% | python | set_merge_lock_held |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | range_vectorcall |
| 0.01% | python | dequeiter_next |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | set_difference_untracked |
| 0.01% | python | range_subscript |
| 0.01% | python | weakref_ref_vectorcall |
| 0.01% | python | _PySlice_GetLongIndices |
| 0.01% | python | set_add |
| 0.01% | python | PySet_Add |
| 0.01% | python | _PySet_NextEntryRef |
| 0.00% | python | set_vectorcall |
| 0.00% | python | bytearray_ass_subscript_lock_held |
| 0.00% | python | set_intersection |
| 0.00% | python | set_iter |
| 0.00% | python | weakref_hash |
| 0.00% | python | weakref_richcompare |
| 0.00% | python | set_discard |
| 0.00% | python | deque_iter |

### str

2.44% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.20% | python | _PyUnicode_Equal |
| 0.19% | python | _PyUnicode_JoinArray.part.0 |
| 0.17% | python | siphash13 |
| 0.16% | python | PyUnicode_Format |
| 0.12% | python | PyUnicode_RichCompare |
| 0.11% | python | _PyUnicode_ResizeCompact |
| 0.11% | python | _copy_characters.constprop.0.isra.0 |
| 0.09% | python | replace |
| 0.07% | python | find_first_nonascii |
| 0.07% | python | unicode_hash |
| 0.06% | python | bytes_richcompare |
| 0.05% | python | PyUnicode_Substring |
| 0.05% | python | unicode_decode_utf8.part.0 |
| 0.04% | python | _PyUnicode_FromUCS4.part.0 |
| 0.04% | python | _PyUnicodeWriter_PrepareInternal |
| 0.04% | python | PyUnicode_Contains |
| 0.03% | python | _PyUnicodeWriter_WriteSubstring |
| 0.03% | python | bytes_translate_impl |
| 0.03% | python | unicode_from_format |
| 0.03% | python | _PyUnicodeWriter_WriteStr |
| 0.03% | python | split |
| 0.03% | python | _PyUnicode_InternMortal |
| 0.03% | python | unicode_repr |
| 0.03% | python | unicode_replace |
| 0.03% | python | PyUnicode_Concat |
| 0.03% | python | bytes_hash |
| 0.02% | python | unicode_decode_utf8_impl |
| 0.02% | python | unicode_join |
| 0.02% | python | _PyUnicode_TranslateCharmap |
| 0.02% | python | _PyUnicode_BinarySlice |
| 0.02% | python | PyUnicode_AsUTF8AndSize |
| 0.02% | python | PyUnicodeWriter_WriteChar |
| 0.02% | python | bytes_subscript |
| 0.02% | python | stringlib_bytes_join_lock_held |
| 0.02% | python | PyBytes_FromStringAndSize |
| 0.02% | python | _PyUnicodeWriter_Finish |
| 0.02% | python | unicode_startswith |
| 0.02% | python | PyUnicodeWriter_WriteStr |
| 0.01% | python | _PyUnicode_FromUCS1.part.0 |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | _PyUnicode_FindMaxChar |
| 0.01% | python | intern_constants |
| 0.01% | python | PyUnicodeWriter_WriteASCII |
| 0.01% | python | unicode_fromformat_write_utf8 |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | _PyUnicode_FromASCII |
| 0.01% | python | bytes_buffer_getbuffer |
| 0.01% | python | _PyUnicode_InternImmortal |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | _PyUnicode_DecodeUTF8Writer |
| 0.01% | python | intern_common |
| 0.01% | python | unicode_rfind |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | PyUnicode_Decode |
| 0.01% | python | PyUnicode_AsEncodedString |
| 0.01% | python | unicode_expandtabs |
| 0.01% | python | _PyUnicode_IsDecimalDigit |
| 0.01% | python | bytes_iteritem |
| 0.01% | python | unicode_strip |
| 0.00% | python | unicode_split |
| 0.00% | python | unicode_encode |
| 0.00% | python | _PyUnicode_XStrip |
| 0.00% | python | unicode_lower |
| 0.00% | python | PyUnicode_Append |
| 0.00% | python | _PyUnicode_FastCopyCharacters |
| 0.00% | python | unicode_mod |
| 0.00% | python | stringlib__two_way |
| 0.00% | python | ascii_decode |
| 0.00% | python | PyUnicode_DecodeUTF8 |
| 0.00% | python | PyUnicode_FindChar |
| 0.00% | python | PyUnicode_FromWideChar |
| 0.00% | python | _PyUnicode_IsDigit |
| 0.00% | python | _PyUnicode_ToLowercase |
| 0.00% | python | bytes_length |
| 0.00% | python | PyUnicode_FromString |
| 0.00% | python | unicode_count_impl |
| 0.00% | python | PyUnicode_InternFromString |
| 0.00% | python | _PyUnicode_FromUCS2.part.0 |
| 0.00% | python | unicode_find |
| 0.00% | python | PyUnicode_AsUCS4 |
| 0.00% | python | unicode_rstrip |
| 0.00% | python | unicode_vectorcall |

### int

2.43% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.73% | python | k_mul |
| 0.19% | python | x_divrem |
| 0.18% | python | long_to_decimal_string_internal |
| 0.15% | python | PyLong_FromSsize_t |
| 0.14% | python | PyLong_FromLong |
| 0.10% | python | PyLong_AsSsize_t |
| 0.09% | python | _PyLong_FromMedium |
| 0.08% | python | long_richcompare |
| 0.07% | python | _PyLong_GCD |
| 0.07% | python | PyLong_AsLongAndOverflow |
| 0.07% | python | x_add |
| 0.06% | python | long_hash |
| 0.04% | python | long_div |
| 0.04% | python | PyLong_FromString |
| 0.03% | python | x_sub |
| 0.03% | python | long_bitwise |
| 0.03% | python | PyLong_FromVoidPtr |
| 0.03% | python | PyLong_AsLong |
| 0.02% | python | PyLong_AsNativeBytes.constprop.0 |
| 0.02% | python | PyLong_FromUnsignedLong |
| 0.02% | python | long_lshift1 |
| 0.02% | python | long_mul |
| 0.02% | python | long_rshift1 |
| 0.02% | python | l_mod |
| 0.02% | python | long_rshift |
| 0.01% | python | long_to_decimal_string |
| 0.01% | python | long_lshift_method |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_neg_method |
| 0.01% | python | _PyLong_Size_t_Converter |
| 0.01% | python | long_add_method |
| 0.01% | python | PyLong_AsDouble |
| 0.01% | python | long_mul_method |
| 0.01% | python | PyLong_FromLongLong |
| 0.01% | python | long_mod |
| 0.01% | python | PyLong_AsInt |
| 0.00% | python | PyLong_FromUnsignedLongLong |
| 0.00% | python | long_float |
| 0.00% | python | long_xor |
| 0.00% | python | PyLong_GetSign |
| 0.00% | python | long_vectorcall |
| 0.00% | python | _PyLong_UInt64_Converter |

### list

2.06% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.34% | python | list_remove |
| 0.32% | python | listiter_next |
| 0.23% | python | list_slice_lock_held |
| 0.17% | python | list_ass_slice_lock_held |
| 0.14% | python | list_iter |
| 0.09% | python | list_sort_impl |
| 0.08% | python | list_slice_wrap |
| 0.08% | python | _PyList_AppendTakeRefListResize |
| 0.07% | python | list_extend_lock_held |
| 0.06% | python | _list_extend |
| 0.06% | python | _PyList_BinarySlice |
| 0.05% | python | list_append |
| 0.05% | python | _PyList_SliceSubscript |
| 0.05% | python | list_ass_subscript |
| 0.04% | python | _PyList_FromStackRefStealOnSuccess |
| 0.04% | python | _PyList_Concat |
| 0.03% | python | list_subscript |
| 0.02% | python | list_contains |
| 0.01% | python | list_length |
| 0.01% | python | list_insert |
| 0.01% | python | list_pop |
| 0.01% | python | PyList_Append |
| 0.01% | python | list_iteritem |
| 0.01% | python | list_sort |
| 0.01% | python | list_vectorcall |
| 0.01% | python | list_to_tuple |
| 0.01% | python | _PyList_Extend |
| 0.00% | python | list_index |
| 0.00% | python | PyList_GetItemRef |
| 0.00% | python | list_richcompare |
| 0.00% | python | _PyList_AsTupleAndClear |
| 0.00% | python | PyList_Size |
| 0.00% | python | PyList_SetItem |
| 0.00% | python | list_extend_dict |

### kernel

2.01% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.22% | [kernel.kallsyms] | __irqentry_text_end |
| 0.11% | [kernel.kallsyms] | error_entry |
| 0.08% | [kernel.kallsyms] | clear_page_erms |
| 0.07% | [kernel.kallsyms] | native_irq_return_iret |
| 0.06% | [kernel.kallsyms] | sync_regs |
| 0.05% | [kernel.kallsyms] | entry_SYSRETQ_unsafe_stack |
| 0.05% | [kernel.kallsyms] | syscall_return_via_sysret |
| 0.03% | [kernel.kallsyms] | __handle_mm_fault |
| 0.03% | [kernel.kallsyms] | do_anonymous_page |
| 0.02% | [kernel.kallsyms] | entry_SYSCALL_64_after_hwframe |
| 0.02% | [kernel.kallsyms] | mas_walk |
| 0.02% | [kernel.kallsyms] | zap_pte_range |
| 0.02% | [kernel.kallsyms] | get_mem_cgroup_from_mm |
| 0.02% | [kernel.kallsyms] | memset_orig |
| 0.02% | [kernel.kallsyms] | __count_memcg_events |
| 0.02% | [kernel.kallsyms] | entry_SYSCALL_64 |
| 0.02% | [kernel.kallsyms] | __alloc_pages |
| 0.02% | [kernel.kallsyms] | handle_mm_fault |
| 0.02% | [kernel.kallsyms] | __rcu_read_unlock |
| 0.02% | [kernel.kallsyms] | lru_gen_add_folio |
| 0.02% | [kernel.kallsyms] | __d_lookup_rcu |
| 0.02% | [kernel.kallsyms] | __rcu_read_lock |
| 0.02% | [kernel.kallsyms] | rep_movs_alternative |
| 0.02% | [kernel.kallsyms] | __mod_memcg_lruvec_state |
| 0.02% | [kernel.kallsyms] | perf_adjust_freq_unthr_context |
| 0.02% | [kernel.kallsyms] | __lruvec_stat_mod_folio |
| 0.01% | [kernel.kallsyms] | __mod_node_page_state |
| 0.01% | [kernel.kallsyms] | _raw_spin_lock |
| 0.01% | [kernel.kallsyms] | percpu_counter_add_batch |
| 0.01% | [kernel.kallsyms] | release_pages |
| 0.01% | [kernel.kallsyms] | link_path_walk.part.0.constprop.0 |
| 0.01% | [kernel.kallsyms] | get_page_from_freelist |
| 0.01% | [kernel.kallsyms] | arch_exit_to_user_mode_prepare.isra.0 |
| 0.01% | [kernel.kallsyms] | lru_gen_del_folio.constprop.0 |
| 0.01% | [kernel.kallsyms] | lru_add_fn |
| 0.01% | [kernel.kallsyms] | folio_add_lru |
| 0.01% | [kernel.kallsyms] | do_user_addr_fault |
| 0.01% | [kernel.kallsyms] | rmqueue |
| 0.01% | [kernel.kallsyms] | cgroup_rstat_updated |
| 0.01% | [kernel.kallsyms] | __pte_offset_map |
| 0.01% | [kernel.kallsyms] | blk_cgroup_congested |
| 0.01% | [kernel.kallsyms] | alloc_anon_folio |
| 0.01% | [kernel.kallsyms] | rmqueue_bulk |
| 0.01% | [kernel.kallsyms] | __pte_offset_map_lock |
| 0.01% | [kernel.kallsyms] | handle_pte_fault |
| 0.01% | [kernel.kallsyms] | kmem_cache_alloc |
| 0.01% | [kernel.kallsyms] | get_vma_policy |
| 0.01% | [kernel.kallsyms] | folio_batch_move_lru |
| 0.01% | [kernel.kallsyms] | exc_page_fault |
| 0.01% | [kernel.kallsyms] | native_write_msr |
| 0.01% | [kernel.kallsyms] | ext4_htree_store_dirent |
| 0.01% | [kernel.kallsyms] | _raw_spin_trylock |
| 0.01% | [kernel.kallsyms] | __mod_zone_page_state |
| 0.01% | [kernel.kallsyms] | lock_vma_under_rcu |
| 0.01% | [kernel.kallsyms] | down_read_trylock |
| 0.01% | [kernel.kallsyms] | do_syscall_64 |
| 0.01% | [kernel.kallsyms] | folio_remove_rmap_ptes |
| 0.01% | [kernel.kallsyms] | __rmqueue_pcplist |
| 0.01% | [kernel.kallsyms] | fpregs_assert_state_consistent |
| 0.01% | [kernel.kallsyms] | pte_offset_map_nolock |
| 0.01% | [kernel.kallsyms] | asm_exc_page_fault |
| 0.01% | [kernel.kallsyms] | folio_add_new_anon_rmap |
| 0.01% | [kernel.kallsyms] | __update_load_avg_se |
| 0.01% | [kernel.kallsyms] | free_unref_page_prepare |
| 0.01% | [kernel.kallsyms] | up_read |
| 0.01% | [kernel.kallsyms] | filldir64 |
| 0.01% | [kernel.kallsyms] | inode_permission |
| 0.01% | [kernel.kallsyms] | mem_cgroup_commit_charge |
| 0.01% | [kernel.kallsyms] | half_md4_transform.isra.0 |
| 0.01% | [kernel.kallsyms] | post_alloc_hook |
| 0.01% | [kernel.kallsyms] | alloc_pages_mpol |
| 0.01% | [kernel.kallsyms] | __update_load_avg_cfs_rq |
| 0.01% | [kernel.kallsyms] | free_unref_page_commit |
| 0.00% | [kernel.kallsyms] | free_unref_page_list |
| 0.00% | [kernel.kallsyms] | uncharge_folio |
| 0.00% | [kernel.kallsyms] | kmem_cache_free |
| 0.00% | [kernel.kallsyms] | generic_permission |
| 0.00% | [kernel.kallsyms] | next_uptodate_folio |
| 0.00% | [kernel.kallsyms] | count_memcg_events.constprop.0 |
| 0.00% | [kernel.kallsyms] | __free_one_page |
| 0.00% | [kernel.kallsyms] | __raw_spin_lock_irqsave |
| 0.00% | [kernel.kallsyms] | strncpy_from_user |
| 0.00% | [kernel.kallsyms] | update_load_avg |
| 0.00% | [kernel.kallsyms] | cond_accept_memory |
| 0.00% | [kernel.kallsyms] | __mem_cgroup_charge |
| 0.00% | [kernel.kallsyms] | __mod_lruvec_state |
| 0.00% | [kernel.kallsyms] | get_pfnblock_flags_mask |
| 0.00% | [kernel.kallsyms] | __hrtimer_run_queues |
| 0.00% | [kernel.kallsyms] | read_tsc |
| 0.00% | [kernel.kallsyms] | __virt_addr_valid |
| 0.00% | [kernel.kallsyms] | update_curr |
| 0.00% | [kernel.kallsyms] | str2hashbuf_signed |
| 0.00% | [kernel.kallsyms] | account_user_time |
| 0.00% | [kernel.kallsyms] | hrtimer_interrupt |
| 0.00% | [kernel.kallsyms] | step_into |
| 0.00% | [kernel.kallsyms] | irqentry_exit_to_user_mode |
| 0.00% | [kernel.kallsyms] | copy_page |
| 0.00% | [kernel.kallsyms] | __kmalloc |
| 0.00% | [kernel.kallsyms] | native_read_msr |
| 0.00% | [kernel.kallsyms] | _raw_spin_unlock |
| 0.00% | [kernel.kallsyms] | consume_stock |
| 0.00% | [kernel.kallsyms] | rb_next |
| 0.00% | [kernel.kallsyms] | vma_alloc_folio |
| 0.00% | [kernel.kallsyms] | try_charge_memcg |
| 0.00% | [kernel.kallsyms] | filemap_map_pages |
| 0.00% | [kernel.kallsyms] | irqentry_exit |
| 0.00% | [kernel.kallsyms] | kfree |
| 0.00% | [kernel.kallsyms] | timekeeping_advance |
| 0.00% | [kernel.kallsyms] | filename_lookup |
| 0.00% | [kernel.kallsyms] | __task_pid_nr_ns |
| 0.00% | [kernel.kallsyms] | apparmor_inode_getattr |
| 0.00% | [kernel.kallsyms] | update_cfs_group |
| 0.00% | [kernel.kallsyms] | __folio_throttle_swaprate |
| 0.00% | [kernel.kallsyms] | pfn_pte |
| 0.00% | [kernel.kallsyms] | error_return |
| 0.00% | [kernel.kallsyms] | set_root |
| 0.00% | [kernel.kallsyms] | x64_sys_call |
| 0.00% | [kernel.kallsyms] | security_inode_permission |
| 0.00% | [kernel.kallsyms] | native_apic_msr_eoi |
| 0.00% | [kernel.kallsyms] | rb_insert_color |
| 0.00% | [kernel.kallsyms] | nohz_balancer_kick |
| 0.00% | [kernel.kallsyms] | scheduler_tick |
| 0.00% | [kernel.kallsyms] | arch_scale_freq_tick |
| 0.00% | [kernel.kallsyms] | cp_new_stat |
| 0.00% | [kernel.kallsyms] | free_swap_cache |
| 0.00% | [kernel.kallsyms] | ktime_get |
| 0.00% | [kernel.kallsyms] | syscall_exit_to_user_mode |
| 0.00% | [kernel.kallsyms] | policy_nodemask |
| 0.00% | [kernel.kallsyms] | __memcg_slab_post_alloc_hook |
| 0.00% | [kernel.kallsyms] | set_ptes.isra.0 |

### tuple

1.35% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.34% | python | PyTuple_FromArray.part.0 |
| 0.31% | python | _PyTuple_FromStackRefStealOnSuccess |
| 0.30% | python | tuple_richcompare |
| 0.18% | python | tuple_hash |
| 0.04% | python | PyTuple_GetSlice |
| 0.03% | python | PyTuple_FromArray |
| 0.03% | python | _PyTuple_FromArraySteal |
| 0.02% | python | tuple_subscript |
| 0.02% | python | _PyTuple_FromPair |
| 0.01% | python | tupleiter_next |
| 0.01% | python | tuplegetter_descr_get |
| 0.01% | python | tuple_iter |
| 0.01% | python | tuple_iteritem |
| 0.01% | python | _PyTuple_FromPairSteal |
| 0.01% | python | _PyTuple_BinarySlice |
| 0.01% | python | _PyTuple_Concat |
| 0.01% | python | tuple_contains |
| 0.01% | python | _PyTuple_Resize |
| 0.00% | python | PyTuple_Pack |
| 0.00% | python | tuple_length |

### calls

0.74% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.21% | python | _PyArg_UnpackKeywords |
| 0.10% | python | PyArg_UnpackTuple |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.08% | python | _Py_CheckFunctionResult |
| 0.07% | python | vgetargs1_impl.constprop.0 |
| 0.04% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.03% | python | PyArg_Parse |
| 0.02% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.02% | python | method_vectorcall_O |
| 0.01% | python | cfunction_vectorcall_NOARGS |
| 0.01% | python | method_vectorcall |
| 0.01% | python | vgetargs1_impl |
| 0.01% | python | vectorcall_method |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | _PyArg_UnpackStack |
| 0.01% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | method_vectorcall_FASTCALL |
| 0.00% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.00% | python | method_vectorcall_NOARGS |
| 0.00% | python | cfunction_vectorcall_FASTCALL |

### threading

0.55% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.29% | python | _PyThreadState_PopFrame |
| 0.15% | python | _PyThreadState_PushFrame |
| 0.08% | python | PyThread_get_thread_ident |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | _PyThreadState_Detach |
| 0.01% | python | _PyThreadState_MustExit |
| 0.00% | python | _PyThreadState_GetCurrent |

### exceptions

0.41% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.15% | python | PyErr_CheckSignals |
| 0.09% | python | _PyErr_CheckSignalsTstate |
| 0.03% | python | PyErr_Occurred |
| 0.03% | python | _PyErr_SetObject.part.0 |
| 0.01% | python | PyErr_ExceptionMatches |
| 0.01% | python | PyTraceBack_Here |
| 0.01% | python | PyErr_GivenExceptionMatches |
| 0.01% | python | _PyErr_Restore |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | BaseException_vectorcall |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | AttributeError_init |
| 0.00% | python | PyErr_Format |
| 0.00% | python | _PyErr_SetKeyError |
| 0.00% | python | PyException_GetTraceback |
| 0.00% | python | _PyErr_CreateException |
| 0.00% | python | PyException_SetTraceback |
| 0.00% | python | PyFrame_GetCode |

### compiler

0.34% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.33% | python | _PyJIT_Entry |
| 0.01% | python | optimize_uops.isra.0 |

### float

0.29% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.19% | python | PyFloat_FromDouble |
| 0.02% | python | float_richcompare |
| 0.02% | python | PyFloat_AsDouble |
| 0.02% | python | float_compactlong_true_div |
| 0.01% | python | float_pow |
| 0.01% | python | float_add |
| 0.00% | python | float_compactlong_guard |
| 0.00% | python | float_vectorcall |

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
| 0.00% | python | r_long |

### async

0.02% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.02% | python | async_gen_anext |
