bin_PROGRAMS = runtime

runtime_SOURCES = 	\
	utility.c 	\
	command.c	\
	rbtree.c

runtime_LDFLAGS = -lpthread -export-dynamic -lreadline -lcurses

include_HEADERS = \
	utility.h \
	command.h \
	rbtree.h

AM_CFLAGS = -Wall -Werror -Wno-error=unused-function # for libtool

#
# tests below:
#

check_PROGRAMS = \
	test_bitmap \
	test_list \
	test_msg_q \
	test_thread_msg_queue \
	test_u64_stat

test_bitmap_SOURCES = test_bitmap.c

test_msg_q_SOURCES = \
	test_msg_q.c \
	rbtree.c \
	utility.c

test_list_SOURCES = test_list.c
test_thread_msg_queue_SOURCES = test_thread_msg_queue.c

test_u64_stat_SOURCES = test_u64_stat.c
test_u64_stat_LDFLAGS = -lm

TESTS = test_bitmap 		\
	test_list		\
	test_thread_msg_queue   \
	test_u64_stat           \
	test_msg_q
