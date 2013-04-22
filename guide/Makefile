all:
	latexmk -xelatex -file-line-error guide 

pvc:
	latexmk -silent -pvc -file-line-error guide

clean:
	-rm *.aux *.bbl *.blg *.log *.toc *.url *.cut *.bib *.run.xml *.bst *.bcf *.fls *.fdb_latexmk *.out *.dvi

distclean: clean
	-rm *.pdf
