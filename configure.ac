AC_INIT([libusbg], [0.1.0], [mporter@linaro.org])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_PROG_CC
AM_PROG_AR
AC_CONFIG_MACRO_DIR([m4])
AC_DEFINE([_GNU_SOURCE], [], [Use GNU extensions])
PKG_CHECK_MODULES(LIBCONFIG, libconfig)
LT_INIT
AC_CONFIG_FILES([Makefile src/Makefile examples/Makefile libusbg.pc])
DX_INIT_DOXYGEN([$PACKAGE_NAME],[doxygen.cfg])
AC_OUTPUT
