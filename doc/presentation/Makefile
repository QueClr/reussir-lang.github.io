all: main.pdf

main.pdf: main.tex
	latexmk -xelatex -shell-escape -interaction=nonstopmode main.tex

clean:
	latexmk -C
	rm -f *.nav *.snm *.vrb

.PHONY: all clean
