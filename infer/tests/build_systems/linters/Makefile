# Copyright (c) 2016-present, Facebook, Inc.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

SYM_ROOT = ../codetoanalyze/linters/tsrc_symlink

TESTS_DIR = ../..
ANALYZER = linters
CLANG_OPTIONS = -x objective-c++ -std=c++11 -fblocks -c
INFER_OPTIONS = --no-filtering --debug-exceptions --project-root $(SYM_ROOT)
INFERPRINT_OPTIONS = --issues-tests

SOURCES = $(SYM_ROOT)/main.mm

include $(TESTS_DIR)/clang.make
