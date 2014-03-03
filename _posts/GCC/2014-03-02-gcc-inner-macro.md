---
layout: post
title: "GCC Inner Macro"
description: "How to print GCC default support macros"
category: GCC
tags: [GCC C Macro]
---
{% include JB/setup %}

# GCC 内建宏查看方法 #
     gcc -dM -E - < /dev/null

## Darwin 输出结果: 
     #define OBJC_NEW_PROPERTIES 1
     #define _LP64 1
     #define __APPLE_CC__ 5621
     #define __APPLE__ 1
     #define __ATOMIC_ACQUIRE 2
     #define __ATOMIC_ACQ_REL 4
     #define __ATOMIC_CONSUME 1
     #define __ATOMIC_RELAXED 0
     #define __ATOMIC_RELEASE 3
     #define __ATOMIC_SEQ_CST 5
     #define __BLOCKS__ 1
     #define __BYTE_ORDER__ __ORDER_LITTLE_ENDIAN__
     #define __CHAR16_TYPE__ unsigned short
     #define __CHAR32_TYPE__ unsigned int
     #define __CHAR_BIT__ 8
     #define __CONSTANT_CFSTRINGS__ 1
     #define __DBL_DENORM_MIN__ 4.9406564584124654e-324
     #define __DBL_DIG__ 15
     #define __DBL_EPSILON__ 2.2204460492503131e-16
     #define __DBL_HAS_DENORM__ 1
     #define __DBL_HAS_INFINITY__ 1
     #define __DBL_HAS_QUIET_NAN__ 1
     #define __DBL_MANT_DIG__ 53
     #define __DBL_MAX_10_EXP__ 308
     #define __DBL_MAX_EXP__ 1024
     #define __DBL_MAX__ 1.7976931348623157e+308
     #define __DBL_MIN_10_EXP__ (-307)
     #define __DBL_MIN_EXP__ (-1021)
     #define __DBL_MIN__ 2.2250738585072014e-308
     #define __DECIMAL_DIG__ 21
     #define __DYNAMIC__ 1
     #define __ENVIRONMENT_MAC_OS_X_VERSION_MIN_REQUIRED__ 1090
     #define __FINITE_MATH_ONLY__ 0
     #define __FLT_DENORM_MIN__ 1.40129846e-45F
     #define __FLT_DIG__ 6
     #define __FLT_EPSILON__ 1.19209290e-7F
     #define __FLT_EVAL_METHOD__ 0
     #define __FLT_HAS_DENORM__ 1
     #define __FLT_HAS_INFINITY__ 1
     #define __FLT_HAS_QUIET_NAN__ 1
     #define __FLT_MANT_DIG__ 24
     #define __FLT_MAX_10_EXP__ 38
     #define __FLT_MAX_EXP__ 128
     #define __FLT_MAX__ 3.40282347e+38F
     #define __FLT_MIN_10_EXP__ (-37)
     #define __FLT_MIN_EXP__ (-125)
     #define __FLT_MIN__ 1.17549435e-38F
     #define __FLT_RADIX__ 2
     #define __GCC_ATOMIC_BOOL_LOCK_FREE 2
     #define __GCC_ATOMIC_CHAR16_T_LOCK_FREE 2
     #define __GCC_ATOMIC_CHAR32_T_LOCK_FREE 2
     #define __GCC_ATOMIC_CHAR_LOCK_FREE 2
     #define __GCC_ATOMIC_INT_LOCK_FREE 2
     #define __GCC_ATOMIC_LLONG_LOCK_FREE 2
     #define __GCC_ATOMIC_LONG_LOCK_FREE 2
     #define __GCC_ATOMIC_POINTER_LOCK_FREE 2
     #define __GCC_ATOMIC_SHORT_LOCK_FREE 2
     #define __GCC_ATOMIC_TEST_AND_SET_TRUEVAL 1
     #define __GCC_ATOMIC_WCHAR_T_LOCK_FREE 2
     #define __GNUC_MINOR__ 2
     #define __GNUC_PATCHLEVEL__ 1
     #define __GNUC_STDC_INLINE__ 1
     #define __GNUC__ 4
     #define __GXX_ABI_VERSION 1002
     #define __GXX_RTTI 1
     #define __INT16_TYPE__ short
     #define __INT32_TYPE__ int
     #define __INT64_C_SUFFIX__ LL
     #define __INT64_TYPE__ long long int
     #define __INT8_TYPE__ char
     #define __INTMAX_MAX__ 9223372036854775807L
     #define __INTMAX_TYPE__ long int
     #define __INTMAX_WIDTH__ 64
     #define __INTPTR_TYPE__ long int
     #define __INTPTR_WIDTH__ 64
     #define __INT_MAX__ 2147483647
     #define __LDBL_DENORM_MIN__ 3.64519953188247460253e-4951L
     #define __LDBL_DIG__ 18
     #define __LDBL_EPSILON__ 1.08420217248550443401e-19L
     #define __LDBL_HAS_DENORM__ 1
     #define __LDBL_HAS_INFINITY__ 1
     #define __LDBL_HAS_QUIET_NAN__ 1
     #define __LDBL_MANT_DIG__ 64
     #define __LDBL_MAX_10_EXP__ 4932
     #define __LDBL_MAX_EXP__ 16384
     #define __LDBL_MAX__ 1.18973149535723176502e+4932L
     #define __LDBL_MIN_10_EXP__ (-4931)
     #define __LDBL_MIN_EXP__ (-16381)
     #define __LDBL_MIN__ 3.36210314311209350626e-4932L
     #define __LITTLE_ENDIAN__ 1
     #define __LONG_LONG_MAX__ 9223372036854775807LL
     #define __LONG_MAX__ 9223372036854775807L
     #define __LP64__ 1
     #define __MACH__ 1
     #define __MMX__ 1
     #define __NO_INLINE__ 1
     #define __NO_MATH_INLINES 1
     #define __ORDER_BIG_ENDIAN__ 4321
     #define __ORDER_LITTLE_ENDIAN__ 1234
     #define __ORDER_PDP_ENDIAN__ 3412
     #define __PIC__ 2
     #define __POINTER_WIDTH__ 64
     #define __PRAGMA_REDEFINE_EXTNAME 1
     #define __PTRDIFF_TYPE__ long int
     #define __PTRDIFF_WIDTH__ 64
     #define __REGISTER_PREFIX__ 
     #define __SCHAR_MAX__ 127
     #define __SHRT_MAX__ 32767
     #define __SIG_ATOMIC_WIDTH__ 32
     #define __SIZEOF_DOUBLE__ 8
     #define __SIZEOF_FLOAT__ 4
     #define __SIZEOF_INT128__ 16
     #define __SIZEOF_INT__ 4
     #define __SIZEOF_LONG_DOUBLE__ 16
     #define __SIZEOF_LONG_LONG__ 8
     #define __SIZEOF_LONG__ 8
     #define __SIZEOF_POINTER__ 8
     #define __SIZEOF_PTRDIFF_T__ 8
     #define __SIZEOF_SHORT__ 2
     #define __SIZEOF_SIZE_T__ 8
     #define __SIZEOF_WCHAR_T__ 4
     #define __SIZEOF_WINT_T__ 4
     #define __SIZE_TYPE__ long unsigned int
     #define __SIZE_WIDTH__ 64
     #define __SSE2_MATH__ 1
     #define __SSE2__ 1
     #define __SSE3__ 1
     #define __SSE_MATH__ 1
     #define __SSE__ 1
     #define __SSP__ 1
     #define __SSSE3__ 1
     #define __STDC_HOSTED__ 1
     #define __STDC_VERSION__ 199901L
     #define __STDC__ 1
     #define __UINTMAX_TYPE__ long unsigned int
     #define __USER_LABEL_PREFIX__ _
     #define __VERSION__ "4.2.1 Compatible Apple LLVM 5.0 (clang-500.2.79)"
     #define __WCHAR_MAX__ 2147483647
     #define __WCHAR_TYPE__ int
     #define __WCHAR_WIDTH__ 32
     #define __WINT_TYPE__ int
     #define __WINT_WIDTH__ 32
     #define __amd64 1
     #define __amd64__ 1
     #define __apple_build_version__ 5000279
     #define __block __attribute__((__blocks__(byref)))
     #define __clang__ 1
     #define __clang_major__ 5
     #define __clang_minor__ 0
     #define __clang_patchlevel__ 0
     #define __clang_version__ "5.0 (clang-500.2.79)"
     #define __core2 1
     #define __core2__ 1
     #define __llvm__ 1
     #define __pic__ 2
     #define __strong 
     #define __tune_core2__ 1
     #define __unsafe_unretained 
     #define __weak __attribute__((objc_gc(weak)))
     #define __x86_64 1
     #define __x86_64__ 1

### Linux GCC 输出
    #define __DBL_MIN_EXP__ (-1021)
    #define __UINT_LEAST16_MAX__ 65535
    #define __FLT_MIN__ 1.17549435082228750797e-38F
    #define __UINT_LEAST8_TYPE__ unsigned char
    #define __INTMAX_C(c) c ## L
    #define __CHAR_BIT__ 8
    #define __UINT8_MAX__ 255
    #define __WINT_MAX__ 4294967295U
    #define __ORDER_LITTLE_ENDIAN__ 1234
    #define __SIZE_MAX__ 18446744073709551615UL
    #define __WCHAR_MAX__ 2147483647
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_1 1
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_2 1
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_4 1
    #define __DBL_DENORM_MIN__ ((double)4.94065645841246544177e-324L)
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_8 1
    #define __FLT_EVAL_METHOD__ 0
    #define __unix__ 1
    #define __x86_64 1
    #define __UINT_FAST64_MAX__ 18446744073709551615UL
    #define __SIG_ATOMIC_TYPE__ int
    #define __DBL_MIN_10_EXP__ (-307)
    #define __FINITE_MATH_ONLY__ 0
    #define __GNUC_PATCHLEVEL__ 3
    #define __UINT_FAST8_MAX__ 255
    #define __DEC64_MAX_EXP__ 385
    #define __INT8_C(c) c
    #define __UINT_LEAST64_MAX__ 18446744073709551615UL
    #define __SHRT_MAX__ 32767
    #define __LDBL_MAX__ 1.18973149535723176502e+4932L
    #define __UINT_LEAST8_MAX__ 255
    #define __UINTMAX_TYPE__ long unsigned int
    #define __linux 1
    #define __DEC32_EPSILON__ 1E-6DF
    #define __unix 1
    #define __UINT32_MAX__ 4294967295U
    #define __LDBL_MAX_EXP__ 16384
    #define __WINT_MIN__ 0U
    #define __linux__ 1
    #define __SCHAR_MAX__ 127
    #define __WCHAR_MIN__ (-__WCHAR_MAX__ - 1)
    #define __INT64_C(c) c ## L
    #define __DBL_DIG__ 15
    #define _FORTIFY_SOURCE 2
    #define __SIZEOF_INT__ 4
    #define __SIZEOF_POINTER__ 8
    #define __USER_LABEL_PREFIX__ 
    #define __STDC_HOSTED__ 1
    #define __LDBL_HAS_INFINITY__ 1
    #define __FLT_EPSILON__ 1.19209289550781250000e-7F
    #define __LDBL_MIN__ 3.36210314311209350626e-4932L
    #define __DEC32_MAX__ 9.999999E96DF
    #define __INT32_MAX__ 2147483647
    #define __SIZEOF_LONG__ 8
    #define __UINT16_C(c) c
    #define __DECIMAL_DIG__ 21
    #define __gnu_linux__ 1
    #define __LDBL_HAS_QUIET_NAN__ 1
    #define __GNUC__ 4
    #define __MMX__ 1
    #define __FLT_HAS_DENORM__ 1
    #define __SIZEOF_LONG_DOUBLE__ 16
    #define __BIGGEST_ALIGNMENT__ 16
    #define __DBL_MAX__ ((double)1.79769313486231570815e+308L)
    #define __INT_FAST32_MAX__ 9223372036854775807L
    #define __DBL_HAS_INFINITY__ 1
    #define __DEC32_MIN_EXP__ (-94)
    #define __INT_FAST16_TYPE__ long int
    #define __LDBL_HAS_DENORM__ 1
    #define __DEC128_MAX__ 9.999999999999999999999999999999999E6144DL
    #define __INT_LEAST32_MAX__ 2147483647
    #define __DEC32_MIN__ 1E-95DF
    #define __DBL_MAX_EXP__ 1024
    #define __DEC128_EPSILON__ 1E-33DL
    #define __SSE2_MATH__ 1
    #define __PTRDIFF_MAX__ 9223372036854775807L
    #define __amd64 1
    #define __LONG_LONG_MAX__ 9223372036854775807LL
    #define __SIZEOF_SIZE_T__ 8
    #define __SIZEOF_WINT_T__ 4
    #define __GCC_HAVE_DWARF2_CFI_ASM 1
    #define __GXX_ABI_VERSION 1002
    #define __FLT_MIN_EXP__ (-125)
    #define __INT_FAST64_TYPE__ long int
    #define __DBL_MIN__ ((double)2.22507385850720138309e-308L)
    #define __LP64__ 1
    #define __DECIMAL_BID_FORMAT__ 1
    #define __DEC128_MIN__ 1E-6143DL
    #define __REGISTER_PREFIX__ 
    #define __UINT16_MAX__ 65535
    #define __DBL_HAS_DENORM__ 1
    #define __UINT8_TYPE__ unsigned char
    #define __NO_INLINE__ 1
    #define __FLT_MANT_DIG__ 24
    #define __VERSION__ "4.6.3"
    #define __UINT64_C(c) c ## UL
    #define __FLOAT_WORD_ORDER__ __ORDER_LITTLE_ENDIAN__
    #define __INT32_C(c) c
    #define __DEC64_EPSILON__ 1E-15DD
    #define __ORDER_PDP_ENDIAN__ 3412
    #define __DEC128_MIN_EXP__ (-6142)
    #define __INT_FAST32_TYPE__ long int
    #define __UINT_LEAST16_TYPE__ short unsigned int
    #define unix 1
    #define __INT16_MAX__ 32767
    #define __SIZE_TYPE__ long unsigned int
    #define __UINT64_MAX__ 18446744073709551615UL
    #define __INT8_TYPE__ signed char
    #define __ELF__ 1
    #define __FLT_RADIX__ 2
    #define __INT_LEAST16_TYPE__ short int
    #define __LDBL_EPSILON__ 1.08420217248550443401e-19L
    #define __UINTMAX_C(c) c ## UL
    #define __SSE_MATH__ 1
    #define __k8 1
    #define __SIG_ATOMIC_MAX__ 2147483647
    #define __SIZEOF_PTRDIFF_T__ 8
    #define __x86_64__ 1
    #define __DEC32_SUBNORMAL_MIN__ 0.000001E-95DF
    #define __INT_FAST16_MAX__ 9223372036854775807L
    #define __UINT_FAST32_MAX__ 18446744073709551615UL
    #define __UINT_LEAST64_TYPE__ long unsigned int
    #define __FLT_HAS_QUIET_NAN__ 1
    #define __FLT_MAX_10_EXP__ 38
    #define __LONG_MAX__ 9223372036854775807L
    #define __DEC128_SUBNORMAL_MIN__ 0.000000000000000000000000000000001E-6143DL
    #define __FLT_HAS_INFINITY__ 1
    #define __UINT_FAST16_TYPE__ long unsigned int
    #define __DEC64_MAX__ 9.999999999999999E384DD
    #define __CHAR16_TYPE__ short unsigned int
    #define __PRAGMA_REDEFINE_EXTNAME 1
    #define __INT_LEAST16_MAX__ 32767
    #define __DEC64_MANT_DIG__ 16
    #define __INT64_MAX__ 9223372036854775807L
    #define __UINT_LEAST32_MAX__ 4294967295U
    #define __INT_LEAST64_TYPE__ long int
    #define __INT16_TYPE__ short int
    #define __INT_LEAST8_TYPE__ signed char
    #define __DEC32_MAX_EXP__ 97
    #define __INT_FAST8_MAX__ 127
    #define __INTPTR_MAX__ 9223372036854775807L
    #define linux 1
    #define __SSE2__ 1
    #define __LDBL_MANT_DIG__ 64
    #define __DBL_HAS_QUIET_NAN__ 1
    #define __SIG_ATOMIC_MIN__ (-__SIG_ATOMIC_MAX__ - 1)
    #define __k8__ 1
    #define __INTPTR_TYPE__ long int
    #define __UINT16_TYPE__ short unsigned int
    #define __WCHAR_TYPE__ int
    #define __SIZEOF_FLOAT__ 4
    #define __UINTPTR_MAX__ 18446744073709551615UL
    #define __DEC64_MIN_EXP__ (-382)
    #define __INT_FAST64_MAX__ 9223372036854775807L
    #define __FLT_DIG__ 6
    #define __UINT_FAST64_TYPE__ long unsigned int
    #define __INT_MAX__ 2147483647
    #define __amd64__ 1
    #define __INT64_TYPE__ long int
    #define __FLT_MAX_EXP__ 128
    #define __ORDER_BIG_ENDIAN__ 4321
    #define __DBL_MANT_DIG__ 53
    #define __INT_LEAST64_MAX__ 9223372036854775807L
    #define __DEC64_MIN__ 1E-383DD
    #define __WINT_TYPE__ unsigned int
    #define __UINT_LEAST32_TYPE__ unsigned int
    #define __SIZEOF_SHORT__ 2
    #define __SSE__ 1
    #define __LDBL_MIN_EXP__ (-16381)
    #define __INT_LEAST8_MAX__ 127
    #define __SSP__ 1
    #define __SIZEOF_INT128__ 16
    #define __LDBL_MAX_10_EXP__ 4932
    #define __DBL_EPSILON__ ((double)2.22044604925031308085e-16L)
    #define _LP64 1
    #define __UINT8_C(c) c
    #define __INT_LEAST32_TYPE__ int
    #define __SIZEOF_WCHAR_T__ 4
    #define __UINT64_TYPE__ long unsigned int
    #define __INT_FAST8_TYPE__ signed char
    #define __DBL_DECIMAL_DIG__ 17
    #define __DEC_EVAL_METHOD__ 2
    #define __UINT32_C(c) c ## U
    #define __INTMAX_MAX__ 9223372036854775807L
    #define __BYTE_ORDER__ __ORDER_LITTLE_ENDIAN__
    #define __FLT_DENORM_MIN__ 1.40129846432481707092e-45F
    #define __INT8_MAX__ 127
    #define __UINT_FAST32_TYPE__ long unsigned int
    #define __CHAR32_TYPE__ unsigned int
    #define __FLT_MAX__ 3.40282346638528859812e+38F
    #define __INT32_TYPE__ int
    #define __SIZEOF_DOUBLE__ 8
    #define __FLT_MIN_10_EXP__ (-37)
    #define __INTMAX_TYPE__ long int
    #define __DEC128_MAX_EXP__ 6145
    #define __GNUC_MINOR__ 6
    #define __UINTMAX_MAX__ 18446744073709551615UL
    #define __DEC32_MANT_DIG__ 7
    #define __DBL_MAX_10_EXP__ 308
    #define __LDBL_DENORM_MIN__ 3.64519953188247460253e-4951L
    #define __INT16_C(c) c
    #define __STDC__ 1
    #define __PTRDIFF_TYPE__ long int
    #define __UINT32_TYPE__ unsigned int
    #define __UINTPTR_TYPE__ long unsigned int
    #define __DEC64_SUBNORMAL_MIN__ 0.000000000000001E-383DD
    #define __DEC128_MANT_DIG__ 34
    #define __LDBL_MIN_10_EXP__ (-4931)
    #define __SIZEOF_LONG_LONG__ 8
    #define __LDBL_DIG__ 18
    #define __FLT_DECIMAL_DIG__ 9
    #define __UINT_FAST16_MAX__ 18446744073709551615UL
    #define __GNUC_GNU_INLINE__ 1
    #define __UINT_FAST8_TYPE__ unsigned char

### Cygwin GCC 输出
    #define __DBL_MIN_EXP__ (-1021)
    #define __pentiumpro__ 1
    #define __UINT_LEAST16_MAX__ 65535
    #define __ATOMIC_ACQUIRE 2
    #define __FLT_MIN__ 1.17549435082228750797e-38F
    #define __UINT_LEAST8_TYPE__ unsigned char
    #define __INTMAX_C(c) c ## LL
    #define __CHAR_BIT__ 8
    #define __UINT8_MAX__ 255
    #define __WINT_MAX__ 4294967295U
    #define __ORDER_LITTLE_ENDIAN__ 1234
    #define __SIZE_MAX__ 4294967295U
    #define __WCHAR_MAX__ 65535
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_1 1
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_2 1
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_4 1
    #define __DBL_DENORM_MIN__ ((double)4.94065645841246544177e-324L)
    #define __GCC_HAVE_SYNC_COMPARE_AND_SWAP_8 1
    #define __GCC_ATOMIC_CHAR_LOCK_FREE 2
    #define __FLT_EVAL_METHOD__ 2
    #define __unix__ 1
    #define __GCC_ATOMIC_CHAR32_T_LOCK_FREE 2
    #define __UINT_FAST64_MAX__ 18446744073709551615ULL
    #define __SIG_ATOMIC_TYPE__ int
    #define __DBL_MIN_10_EXP__ (-307)
    #define __FINITE_MATH_ONLY__ 0
    #define __GNUC_PATCHLEVEL__ 3
    #define __UINT_FAST8_MAX__ 255
    #define _stdcall __attribute__((__stdcall__))
    #define __DEC64_MAX_EXP__ 385
    #define __INT8_C(c) c
    #define __UINT_LEAST64_MAX__ 18446744073709551615ULL
    #define __SHRT_MAX__ 32767
    #define __LDBL_MAX__ 1.18973149535723176502e+4932L
    #define __UINT_LEAST8_MAX__ 255
    #define __GCC_ATOMIC_BOOL_LOCK_FREE 2
    #define __UINTMAX_TYPE__ long long unsigned int
    #define __DEC32_EPSILON__ 1E-6DF
    #define __unix 1
    #define __UINT32_MAX__ 4294967295U
    #define __LDBL_MAX_EXP__ 16384
    #define __WINT_MIN__ 0U
    #define __SCHAR_MAX__ 127
    #define __WCHAR_MIN__ 0
    #define __INT64_C(c) c ## LL
    #define __DBL_DIG__ 15
    #define __GCC_ATOMIC_POINTER_LOCK_FREE 2
    #define __SIZEOF_INT__ 4
    #define __SIZEOF_POINTER__ 4
    #define __USER_LABEL_PREFIX__ _
    #define __STDC_HOSTED__ 1
    #define __LDBL_HAS_INFINITY__ 1
    #define __FLT_EPSILON__ 1.19209289550781250000e-7F
    #define __LDBL_MIN__ 3.36210314311209350626e-4932L
    #define __DEC32_MAX__ 9.999999E96DF
    #define __INT32_MAX__ 2147483647
    #define __SIZEOF_LONG__ 4
    #define __UINT16_C(c) c
    #define __DECIMAL_DIG__ 21
    #define __LDBL_HAS_QUIET_NAN__ 1
    #define __GNUC__ 4
    #define _cdecl __attribute__((__cdecl__))
    #define __FLT_HAS_DENORM__ 1
    #define __SIZEOF_LONG_DOUBLE__ 12
    #define __BIGGEST_ALIGNMENT__ 16
    #define __i686 1
    #define __DBL_MAX__ ((double)1.79769313486231570815e+308L)
    #define _thiscall __attribute__((__thiscall__))
    #define __INT_FAST32_MAX__ 2147483647
    #define __DBL_HAS_INFINITY__ 1
    #define __DEC32_MIN_EXP__ (-94)
    #define __INT_FAST16_TYPE__ int
    #define _fastcall __attribute__((__fastcall__))
    #define __LDBL_HAS_DENORM__ 1
    #define __DEC128_MAX__ 9.999999999999999999999999999999999E6144DL
    #define __INT_LEAST32_MAX__ 2147483647
    #define __DEC32_MIN__ 1E-95DF
    #define __DBL_MAX_EXP__ 1024
    #define __DEC128_EPSILON__ 1E-33DL
    #define __PTRDIFF_MAX__ 2147483647
    #define __LONG_LONG_MAX__ 9223372036854775807LL
    #define __SIZEOF_SIZE_T__ 4
    #define __SIZEOF_WINT_T__ 4
    #define __GCC_HAVE_DWARF2_CFI_ASM 1
    #define __GXX_ABI_VERSION 1002
    #define __FLT_MIN_EXP__ (-125)
    #define __i686__ 1
    #define __INT_FAST64_TYPE__ long long int
    #define __DBL_MIN__ ((double)2.22507385850720138309e-308L)
    #define __DECIMAL_BID_FORMAT__ 1
    #define __GXX_TYPEINFO_EQUALITY_INLINE 0
    #define __DEC128_MIN__ 1E-6143DL
    #define __REGISTER_PREFIX__
    #define __UINT16_MAX__ 65535
    #define __DBL_HAS_DENORM__ 1
    #define __cdecl __attribute__((__cdecl__))
    #define __UINT8_TYPE__ unsigned char
    #define __NO_INLINE__ 1
    #define __i386 1
    #define __FLT_MANT_DIG__ 24
    #define __VERSION__ "4.7.3"
    #define __UINT64_C(c) c ## ULL
    #define __GCC_ATOMIC_INT_LOCK_FREE 2
    #define _X86_ 1
    #define __FLOAT_WORD_ORDER__ __ORDER_LITTLE_ENDIAN__
    #define __INT32_C(c) c
    #define __DEC64_EPSILON__ 1E-15DD
    #define __ORDER_PDP_ENDIAN__ 3412
    #define __DEC128_MIN_EXP__ (-6142)
    #define __code_model_32__ 1
    #define __INT_FAST32_TYPE__ int
    #define __UINT_LEAST16_TYPE__ short unsigned int
    #define unix 1
    #define __INT16_MAX__ 32767
    #define __i386__ 1
    #define __SIZE_TYPE__ unsigned int
    #define __UINT64_MAX__ 18446744073709551615ULL
    #define __INT8_TYPE__ signed char
    #define __FLT_RADIX__ 2
    #define __INT_LEAST16_TYPE__ short int
    #define __LDBL_EPSILON__ 1.08420217248550443401e-19L
    #define __UINTMAX_C(c) c ## ULL
    #define __SIG_ATOMIC_MAX__ 2147483647
    #define __GCC_ATOMIC_WCHAR_T_LOCK_FREE 2
    #define __SIZEOF_PTRDIFF_T__ 4
    #define __CYGWIN__ 1
    #define __DEC32_SUBNORMAL_MIN__ 0.000001E-95DF
    #define __pentiumpro 1
    #define __INT_FAST16_MAX__ 2147483647
    #define __UINT_FAST32_MAX__ 4294967295U
    #define __UINT_LEAST64_TYPE__ long long unsigned int
    #define __FLT_HAS_QUIET_NAN__ 1
    #define __FLT_MAX_10_EXP__ 38
    #define __LONG_MAX__ 2147483647L
    #define __DEC128_SUBNORMAL_MIN__ 0.000000000000000000000000000000001E-6143DL
    #define __FLT_HAS_INFINITY__ 1
    #define __UINT_FAST16_TYPE__ unsigned int
    #define __DEC64_MAX__ 9.999999999999999E384DD
    #define __CHAR16_TYPE__ short unsigned int
    #define __PRAGMA_REDEFINE_EXTNAME 1
    #define __INT_LEAST16_MAX__ 32767
    #define __DEC64_MANT_DIG__ 16
    #define __INT64_MAX__ 9223372036854775807LL
    #define __UINT_LEAST32_MAX__ 4294967295U
    #define __GCC_ATOMIC_LONG_LOCK_FREE 2
    #define __INT_LEAST64_TYPE__ long long int
    #define __INT16_TYPE__ short int
    #define __INT_LEAST8_TYPE__ signed char
    #define __DEC32_MAX_EXP__ 97
    #define __INT_FAST8_MAX__ 127
    #define __INTPTR_MAX__ 2147483647
    #define __GXX_MERGED_TYPEINFO_NAMES 0
    #define __stdcall __attribute__((__stdcall__))
    #define __LDBL_MANT_DIG__ 64
    #define __DBL_HAS_QUIET_NAN__ 1
    #define __SIG_ATOMIC_MIN__ (-__SIG_ATOMIC_MAX__ - 1)
    #define __INTPTR_TYPE__ int
    #define __UINT16_TYPE__ short unsigned int
    #define __WCHAR_TYPE__ short unsigned int
    #define __SIZEOF_FLOAT__ 4
    #define __UINTPTR_MAX__ 4294967295U
    #define __DEC64_MIN_EXP__ (-382)
    #define __INT_FAST64_MAX__ 9223372036854775807LL
    #define __GCC_ATOMIC_TEST_AND_SET_TRUEVAL 1
    #define __FLT_DIG__ 6
    #define __UINT_FAST64_TYPE__ long long unsigned int
    #define __INT_MAX__ 2147483647
    #define __INT64_TYPE__ long long int
    #define __FLT_MAX_EXP__ 128
    #define __DBL_MANT_DIG__ 53
    #define __INT_LEAST64_MAX__ 9223372036854775807LL
    #define __GCC_ATOMIC_CHAR16_T_LOCK_FREE 2
    #define __DEC64_MIN__ 1E-383DD
    #define __WINT_TYPE__ unsigned int
    #define __UINT_LEAST32_TYPE__ unsigned int
    #define __SIZEOF_SHORT__ 2
    #define __LDBL_MIN_EXP__ (-16381)
    #define __INT_LEAST8_MAX__ 127
    #define __LDBL_MAX_10_EXP__ 4932
    #define __ATOMIC_RELAXED 0
    #define __DBL_EPSILON__ ((double)2.22044604925031308085e-16L)
    #define __thiscall __attribute__((__thiscall__))
    #define __UINT8_C(c) c
    #define __INT_LEAST32_TYPE__ int
    #define __SIZEOF_WCHAR_T__ 2
    #define __UINT64_TYPE__ long long unsigned int
    #define __INT_FAST8_TYPE__ signed char
    #define __fastcall __attribute__((__fastcall__))
    #define __CYGWIN32__ 1
    #define __DBL_DECIMAL_DIG__ 17
    #define __DEC_EVAL_METHOD__ 2
    #define __ORDER_BIG_ENDIAN__ 4321
    #define __UINT32_C(c) c ## U
    #define __INTMAX_MAX__ 9223372036854775807LL
    #define __BYTE_ORDER__ __ORDER_LITTLE_ENDIAN__
    #define __FLT_DENORM_MIN__ 1.40129846432481707092e-45F
    #define __INT8_MAX__ 127
    #define __UINT_FAST32_TYPE__ unsigned int
    #define __CHAR32_TYPE__ unsigned int
    #define __FLT_MAX__ 3.40282346638528859812e+38F
    #define __INT32_TYPE__ int
    #define __SIZEOF_DOUBLE__ 8
    #define __FLT_MIN_10_EXP__ (-37)
    #define __INTMAX_TYPE__ long long int
    #define i386 1
    #define __DEC128_MAX_EXP__ 6145
    #define __ATOMIC_CONSUME 1
    #define __GNUC_MINOR__ 7
    #define __UINTMAX_MAX__ 18446744073709551615ULL
    #define __DEC32_MANT_DIG__ 7
    #define __DBL_MAX_10_EXP__ 308
    #define __LDBL_DENORM_MIN__ 3.64519953188247460253e-4951L
    #define __INT16_C(c) c
    #define __STDC__ 1
    #define __PTRDIFF_TYPE__ int
    #define __ATOMIC_SEQ_CST 5
    #define __UINT32_TYPE__ unsigned int
    #define __UINTPTR_TYPE__ unsigned int
    #define __DEC64_SUBNORMAL_MIN__ 0.000000000000001E-383DD
    #define __DEC128_MANT_DIG__ 34
    #define __LDBL_MIN_10_EXP__ (-4931)
    #define __SIZEOF_LONG_LONG__ 8
    #define __GCC_ATOMIC_LLONG_LOCK_FREE 2
    #define __LDBL_DIG__ 18
    #define __FLT_DECIMAL_DIG__ 9
    #define __UINT_FAST16_MAX__ 4294967295U
    #define __GNUC_GNU_INLINE__ 1
    #define __GCC_ATOMIC_SHORT_LOCK_FREE 2
    #define __UINT_FAST8_TYPE__ unsigned char
    #define __ATOMIC_ACQ_REL 4
    #define __ATOMIC_RELEASE 3
    #define __declspec(x) __attribute__((x))

