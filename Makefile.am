SUBDIRS = subdir-1 subdir-2

TESTS =	test-sample/prepare-test.sh		\
	test-sample/case-0/case-test.sh		\
	test-sample/case-1/case-test.sh		\
	test-sample/case-2/case-test.sh		\
	test-sample/case-3/case-test.sh		\
	test-sample/case-4/case-test.sh		\
	test-sample/case-5/case-test.sh		\
	test-sample/case-6/case-test.sh		\
	test-sample/case-7/case-test.sh

install-exec-hook:
	@cp -r $(srcdir)/3rd-party $(DESTDIR)
