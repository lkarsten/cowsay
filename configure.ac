
AC_PREREQ([2.69])
AC_INIT([cowsay], [0.1], [lkarsten@varnish-software.com])
AC_CONFIG_SRCDIR([src])
AC_CONFIG_HEADERS([config.h])

AM_INIT_AUTOMAKE([foreign color-tests parallel-tests])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET

AM_MAINTAINER_MODE([disable])


# Checks for header files.
AC_CHECK_HEADERS([stdlib.h unistd.h])

SH_TESTS="$(cd $srcdir/src && echo tests/test*.sh)"
AC_SUBST(SH_TESTS)

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT



