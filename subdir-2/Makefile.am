bin_PROGRAMS = get-app-layer-info
get_app_layer_info_SOURCES = src/get-app-layer-info.c

# TODO: add test_init-module-dir.sh
TESTS =	\
	test-lispscript/test-copy-record.sh		\
	test-lispscript/test-cartesian.sh		\
	test-bashscript/test-user-parameter/case_1/case_test.sh

dist_bin_SCRIPTS = 				\
	env.sh					\
	init-module-dir 			\
	build-module	 			\
	get-module-info				\
	gen-runtime-info			\
	run-module                 		\
	update-module				\
	gen-module-c-code			\
	gen-main-c-code				\
	alist.ss				\
	cartesian.ss				\
	gen-user-parameters-so			\
	wire.ss

templatedir=$(datadir)
nobase_dist_template_DATA = template/*
AM_CPPFLAGS = -I../runtime
