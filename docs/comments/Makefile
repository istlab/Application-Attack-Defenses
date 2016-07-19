
.SUFFIXES:.eps .pdf .gz .data .dot

comments.pdf: comments.tex comments.bib
	pdflatex comments
	bibtex comments
	pdflatex comments
	pdflatex comments

clean:
	rm -f comments.aux comments.bbl comments.blg comments.log comments.out comments.pdf
