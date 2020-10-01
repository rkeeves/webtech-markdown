sources = $(wildcard *.md)
targets = $(sources:.md=.pdf)

PDF_ENG = pdflatex

PANDOC = pandoc
PANDOC_FLAGS = -t latex --pdf-engine=$(PDF_ENG)

.PHONY: all
all: $(targets)

%.pdf: %.md
	$(PANDOC) $< -o $@ $(PANDOC_FLAGS)

.PHONY: clean
clean:
	rm -f $(targets)
