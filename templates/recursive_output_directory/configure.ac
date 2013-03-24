#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AC_CONFIG_SRCDIR([libCube/include/cube.hpp])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE
LT_INIT

# Checks for programs.
AC_PROG_CXX

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

SOLUTION_DIR=`pwd`
OUTPUT_DIR=${SOLUTION_DIR}/output
AC_SUBST(SOLUTION_DIR)
AC_SUBST(OUTPUT_DIR)

AC_CONFIG_FILES([Makefile libCube/Makefile testCube/Makefile])
AC_OUTPUT
