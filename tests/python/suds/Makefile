ROOT_DIR=$(shell pwd)/../../..

include $(ROOT_DIR)/Makefile.common
include $(TEST_DIR)/Makefile.common

build_local:

test:
	unit2 discover -t . -s testcases -p '*.py'

clean_local:
