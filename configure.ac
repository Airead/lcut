#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([lcut], [0.3.0], [fgh1987168])
AC_CONFIG_SRCDIR([src/lcut.h])
AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE(lcut, 0.3.0)

AC_CONFIG_MACRO_DIR([m4])

CFLAGS="-g -Wall -O0"
# Checks for programs.
AC_PROG_CC

# Checks for libraries.
LT_INIT

# Checks for header files.
AC_CHECK_HEADERS([stddef.h stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS([memset])

AC_CONFIG_FILES([Makefile
                 src/Makefile
                 src/example/Makefile])
AC_OUTPUT
