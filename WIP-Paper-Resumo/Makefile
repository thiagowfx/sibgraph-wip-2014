all:
	pdflatex -interaction nonstopmode example.tex
	bibtex example
	pdflatex -interaction nonstopmode example.tex
	bibtex example
	pdflatex -interaction nonstopmode example.tex
clean:	
	rm *.{aux,bbl,blg,log}
