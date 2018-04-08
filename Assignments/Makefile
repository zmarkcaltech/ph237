#!/usr/bin/make -f
.PHONY: all clean
all: a1

a1: %: %.tex
	latexmk -pdf $@


.PHONY: clean
clean:
	latexmk -C
