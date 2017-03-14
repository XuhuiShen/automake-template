AC_INIT([automake-template], [0.3.0], [shenxuhui@ict.ac.cn])
AC_CONFIG_AUX_DIR([.])
AM_INIT_AUTOMAKE([-Wall -Werror foreign subdir-objects])
AM_PROG_AR
LT_INIT

AC_PROG_CC
AM_PROG_CC_C_O
AC_CHECK_LIB(dl, dlopen)
AC_CHECK_LIB(dl, dlerror)
AM_SILENT_RULES([yes])

AC_CONFIG_FILES([
	Makefile
	subdir-1/Makefile
	subdir-2/Makefile])

AC_OUTPUT
