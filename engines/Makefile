INCLUDES=-I..

OBJS=joseki.o josekibase.o montecarlo.o patternplay.o patternscan.o random.o replay.o

ifeq ($(DCNN), 1)
	OBJS+=dcnn.o
endif

all: lib.a
lib.a: $(OBJS)


-include ../Makefile.lib
