#!/usr/bin/make -f
.PHONY: all clean
all: a1 a2

a1: %: %.tex
	latexmk -pdf $@

a2: %: %.tex
	latexmk -pdf $@


.PHONY: clean
clean:
	latexmk -C
