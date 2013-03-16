
CFLAGS	+= -I..

target-y = \
	arraysort \
	arraysort1 \
	arraybinsearch \
	listsort \
	listinsertsort \
	listinsertsort1 \
	rbtree \
	dllist \
	hash \
	selftest

arraysort_files-y = arraysort.c

arraysort1_files-y = arraysort1.c

arraybinsearch_files-y = arraybinsearch.c

listsort_files-y = listsort.c

dllist_files-y = dllist.c

hash_files-y = hash.c

listinsertsort_files-y = listinsertsort.c

listinsertsort1_files-y = listinsertsort1.c

rbtree_files-y = rbtree.c

selftest_files-y = selftest.c

tests: all
	./arraysort 6 7 3 4 1 4 1 3 5
	./arraysort1 6 7 3 4 1 4 1 3 5
	./arraybinsearch 6 7 3 4 1 4 1 3 5
	./listsort 6 7 3 4 1 4 1 3 5
	./dllist 6 7 3 4 1 4 1 3 5
	./hash 1 3 5 2 3 1 7 11 33 11
	./listinsertsort 6 7 3 4 1 4 1 3 5
	./listinsertsort1 6 7 3 4 1 4 1 3 5
	./rbtree 6 7 3 4 1 4 1 3 5
	./selftest
	@echo Done

include Makefile.lib
