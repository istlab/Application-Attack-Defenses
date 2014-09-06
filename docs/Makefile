
.SUFFIXES:.eps .pdf .gz .data .dot

questioning.pdf: questioning.tex questioning.bib
	pdflatex questioning
	bibtex questioning
	pdflatex questioning
	pdflatex questioning

clean:
	rm -f questioning.aux questioning.bbl questioning.blg questioning.log questioning.out questioning.pdf
