#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])

AC_INIT([hidindicator], [1.0.0])


AC_ARG_WITH([udevdir],
  [AS_HELP_STRING([--with-udevdir=DIR], [udev files])],
  [udevdir=$withval],
  [udevdir="/lib/udev/rules.d"])
AC_SUBST([udevdir], [$udevdir])

AM_INIT_AUTOMAKE

AC_PREFIX_DEFAULT(/usr)

AC_OUTPUT(Makefile scripts/Makefile rules/Makefile)
