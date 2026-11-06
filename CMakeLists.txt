
set(PDCLIB_SOURCES
    functions/ctype/isalnum.c
    functions/ctype/isalpha.c
    functions/ctype/isblank.c
    functions/ctype/iscntrl.c
    functions/ctype/isdigit.c
    functions/ctype/isgraph.c
    functions/ctype/islower.c
    functions/ctype/isprint.c
    functions/ctype/ispunct.c
    functions/ctype/isspace.c
    functions/ctype/isupper.c
    functions/ctype/isxdigit.c
    functions/ctype/tolower.c
    functions/ctype/toupper.c

    functions/inttypes/imaxabs.c
    functions/inttypes/imaxdiv.c
    functions/inttypes/strtoimax.c
    functions/inttypes/strtoumax.c

    functions/locale/localeconv.c
    functions/locale/setlocale.c

    functions/math/fabs.c
    functions/math/fdim.c
    functions/math/fmax.c
    functions/math/fmin.c
    functions/math/fpclassify.c
    functions/math/isfinite.c
    functions/math/isinf.c
    functions/math/isnan.c
    functions/math/isnormal.c
    functions/math/signbit.c

    functions/stdio/clearerr.c
    functions/stdio/fclose.c
    functions/stdio/feof.c
    functions/stdio/ferror.c
    functions/stdio/fflush.c
    functions/stdio/fgetc.c
    functions/stdio/fgetpos.c
    functions/stdio/fgets.c
    functions/stdio/fopen.c
    functions/stdio/fopen_s.c
    functions/stdio/fprintf.c
    functions/stdio/fputc.c
    functions/stdio/fputs.c
    functions/stdio/fread.c
    functions/stdio/freopen.c
    functions/stdio/freopen_s.c
    functions/stdio/fscanf.c
    functions/stdio/fseek.c
    functions/stdio/fsetpos.c
    functions/stdio/ftell.c
    functions/stdio/fwrite.c
    functions/stdio/getc.c
    functions/stdio/getchar.c
    functions/stdio/perror.c
    functions/stdio/printf.c
    functions/stdio/putc.c
    functions/stdio/putchar.c
    functions/stdio/puts.c
    # functions/stdio/remove.c
    functions/stdio/rename.c
    functions/stdio/rewind.c
    functions/stdio/scanf.c
    functions/stdio/setbuf.c
    functions/stdio/setvbuf.c
    functions/stdio/snprintf.c
    functions/stdio/sprintf.c
    functions/stdio/sscanf.c
    functions/stdio/tmpfile_s.c
    functions/stdio/tmpnam.c
    functions/stdio/ungetc.c
    functions/stdio/vfprintf.c
    functions/stdio/vfscanf.c
    functions/stdio/vprintf.c
    functions/stdio/vscanf.c
    functions/stdio/vsnprintf.c
    functions/stdio/vsprintf.c
    functions/stdio/vsscanf.c

    functions/stdlib/abort.c
    functions/stdlib/abort_handler_s.c
    functions/stdlib/abs.c
    functions/stdlib/at_quick_exit.c
    functions/stdlib/atexit.c
    functions/stdlib/atoi.c
    functions/stdlib/atol.c
    functions/stdlib/atoll.c
    functions/stdlib/bsearch.c
    functions/stdlib/bsearch_s.c
    functions/stdlib/div.c
    functions/stdlib/exit.c
    functions/stdlib/_Exit.c
    functions/stdlib/ignore_handler_s.c
    functions/stdlib/labs.c
    functions/stdlib/ldiv.c
    functions/stdlib/llabs.c
    functions/stdlib/lldiv.c
    functions/stdlib/qsort.c
    functions/stdlib/qsort_s.c
    functions/stdlib/quick_exit.c
    functions/stdlib/rand.c
    functions/stdlib/set_constraint_handler_s.c
    functions/stdlib/srand.c
    functions/stdlib/strtod.c
    functions/stdlib/strtof.c
    functions/stdlib/strtold.c
    functions/stdlib/strtol.c
    functions/stdlib/strtoll.c
    functions/stdlib/strtoul.c
    functions/stdlib/strtoull.c

    functions/string/memchr.c
    functions/string/memcmp.c
    functions/string/memcpy.c
    functions/string/memmove.c
    functions/string/memset.c
    functions/string/strcat.c
    functions/string/strchr.c
    functions/string/strcmp.c
    functions/string/strcoll.c
    functions/string/strcpy.c
    functions/string/strcspn.c
    functions/string/strerror.c
    functions/string/strlen.c
    functions/string/strncat.c
    functions/string/strncmp.c
    functions/string/strncpy.c
    functions/string/strpbrk.c
    functions/string/strrchr.c
    functions/string/strspn.c
    functions/string/strstr.c
    functions/string/strtok.c
    functions/string/strtok_s.c
    functions/string/strxfrm.c
    functions/string/memcpy_s.c
    functions/string/memmove_s.c
    functions/string/memset_s.c
    functions/string/strcat_s.c
    functions/string/strcpy_s.c
    functions/string/strerror_s.c
    functions/string/strerrorlen_s.c
    functions/string/strncat_s.c
    functions/string/strncpy_s.c

    functions/_tzcode/_PDCLIB_gmtcheck.c
    functions/_tzcode/_PDCLIB_gmtsub.c
    functions/_tzcode/_PDCLIB_increment_overflow.c
    functions/_tzcode/_PDCLIB_init_ttinfo.c
    functions/_tzcode/_PDCLIB_localsub.c
    functions/_tzcode/_PDCLIB_localtime_tzset.c
    functions/_tzcode/_PDCLIB_mktime_tzname.c
    functions/_tzcode/_PDCLIB_timesub.c
    functions/_tzcode/_PDCLIB_tzload.c
    functions/_tzcode/_PDCLIB_tzparse.c
    functions/_tzcode/_PDCLIB_tzset_unlocked.c
    functions/_tzcode/_PDCLIB_update_tzname_etc.c

    functions/_PDCLIB/assert.c
    functions/_PDCLIB/errno.c
    functions/_PDCLIB/_PDCLIB_atomax.c
    functions/_PDCLIB/_PDCLIB_fp_from_dbl.c
    functions/_PDCLIB/_PDCLIB_fp_from_ldbl.c
    functions/_PDCLIB/_PDCLIB_bigint_add.c
    functions/_PDCLIB/_PDCLIB_bigint_cmp.c
    functions/_PDCLIB/_PDCLIB_bigint_digit_log2.c
    functions/_PDCLIB/_PDCLIB_bigint_div.c
    functions/_PDCLIB/_PDCLIB_bigint_from_bigint.c
    functions/_PDCLIB/_PDCLIB_bigint_from_digit.c
    functions/_PDCLIB/_PDCLIB_bigint_from_pow10.c
    functions/_PDCLIB/_PDCLIB_bigint_from_pow2.c
    functions/_PDCLIB/_PDCLIB_bigint_log2.c
    functions/_PDCLIB/_PDCLIB_bigint_mul.c
    functions/_PDCLIB/_PDCLIB_bigint_mul10.c
    functions/_PDCLIB/_PDCLIB_bigint_mul_pow10.c
    functions/_PDCLIB/_PDCLIB_bigint_shl.c
    functions/_PDCLIB/_PDCLIB_closeall.c
    functions/_PDCLIB/_PDCLIB_digits.c
    functions/_PDCLIB/_PDCLIB_filemode.c
    functions/_PDCLIB/_PDCLIB_getstream.c
    functions/_PDCLIB/_PDCLIB_init_file_t.c
    functions/_PDCLIB/_PDCLIB_is_leap.c
    functions/_PDCLIB/_PDCLIB_isstream.c
    functions/_PDCLIB/_PDCLIB_load_lc_collate.c
    functions/_PDCLIB/_PDCLIB_load_lc_ctype.c
    functions/_PDCLIB/_PDCLIB_load_lc_messages.c
    functions/_PDCLIB/_PDCLIB_load_lc_monetary.c
    functions/_PDCLIB/_PDCLIB_load_lc_numeric.c
    functions/_PDCLIB/_PDCLIB_load_lc_time.c
    functions/_PDCLIB/_PDCLIB_load_lines.c
    functions/_PDCLIB/_PDCLIB_naive_etod.c
    functions/_PDCLIB/_PDCLIB_naive_ptod.c
    functions/_PDCLIB/_PDCLIB_prepread.c
    functions/_PDCLIB/_PDCLIB_prepwrite.c
    functions/_PDCLIB/_PDCLIB_print.c
    functions/_PDCLIB/_PDCLIB_print_fp.c
    functions/_PDCLIB/_PDCLIB_print_fp_deci.c
    functions/_PDCLIB/_PDCLIB_print_fp_hexa.c
    functions/_PDCLIB/_PDCLIB_print_integer.c
    functions/_PDCLIB/_PDCLIB_print_string.c
    functions/_PDCLIB/_PDCLIB_scan.c
    functions/_PDCLIB/_PDCLIB_seed.c
    functions/_PDCLIB/_PDCLIB_strtok.c
    functions/_PDCLIB/_PDCLIB_strtod_prelim.c
    functions/_PDCLIB/_PDCLIB_strtox_main.c
    functions/_PDCLIB/_PDCLIB_strtox_prelim.c
    functions/_PDCLIB/stdarg.c

    # platform/example/functions/_PDCLIB/_PDCLIB_changemode.c
    # platform/example/functions/_PDCLIB/_PDCLIB_close.c
    # platform/example/functions/_PDCLIB/_PDCLIB_Exit.c
    # platform/example/functions/_PDCLIB/_PDCLIB_fillbuffer.c
    # platform/example/functions/_PDCLIB/_PDCLIB_flushbuffer.c
    # platform/example/functions/_PDCLIB/_PDCLIB_open.c
    # platform/example/functions/_PDCLIB/_PDCLIB_realpath.c
    # platform/example/functions/_PDCLIB/_PDCLIB_rename.c
    # platform/example/functions/_PDCLIB/_PDCLIB_remove.c
    # platform/example/functions/_PDCLIB/_PDCLIB_seek.c
    platform/example/functions/_PDCLIB/_PDCLIB_stdinit.c
)

set(__STDC_NO_THREADS__ 1)

set(PDCLIB_GENERATE_INCLUDE_DIR
    "${CMAKE_CURRENT_BINARY_DIR}/configured_include"
)

configure_file(
    "${CMAKE_CURRENT_SOURCE_DIR}/platform/l4/include/pdclib/_PDCLIB_config.h"
    "${PDCLIB_GENERATE_INCLUDE_DIR}/pdclib/_PDCLIB_config.h"
    @ONLY
)

add_library(pdc STATIC ${PDCLIB_SOURCES})

l4_compile(pdc 64)

target_compile_definitions(pdc PRIVATE
    _PDCLIB_BUILD
    _PDCLIB_STATIC_DEFINE
)

target_include_directories(pdc BEFORE PUBLIC
    "${PDCLIB_GENERATE_INCLUDE_DIR}"
    "${CMAKE_CURRENT_SOURCE_DIR}/include"
    "${CMAKE_CURRENT_SOURCE_DIR}/platform/l4/include"
)