# Copyright (C) 2008-2013 Assaf Gordon <assafgordon@gmail.com>
#  
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without 
# modifications, as long as this notice is preserved.
# 
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.


noinst_PROGRAMS = seqalign_test 

AM_CPPFLAGS = \
	$(CC_WARNINGS) \
	-I$(top_srcdir)/src/libfastx

seqalign_test_SOURCES = seqalign_test.cpp

seqalign_test_LDADD = ../libfastx/libfastx.a

