#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT(hiboi, 1.0, hugh.stuckless@hotmail.com)
AC_CONFIG_SRCDIR([src/bin/main.c])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE

# Checks for programs.
AC_PROG_CC
AC_PROG_CPP
AC_PROG_RANLIB
# Use C compiler
AC_LANG([C])
# Checks for libraries.

# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([stdio.h])
# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T
# Checks for library functions.

AC_CONFIG_FILES([Makefile
                 src/bin/Makefile
                 src/lib/Makefile])
AC_OUTPUT
