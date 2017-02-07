all: cv.pdf

open: cv.pdf
	open cv.pdf

cv.pdf: *.tex cv.bib 
	pdflatex cv.tex
	bibtex cv
	pdflatex cv.tex
	pdflatex cv.tex

clean:  
	rm -f cv.pdf *.aux *.blg *.bbl *.log *.tmp *.xref *.idv *.4og *.4ct *.lg *.4tc *.out *~
