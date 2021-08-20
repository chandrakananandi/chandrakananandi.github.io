TEX=$(wildcard *.tex)
BIB=$(wildcard *.bib)

chandrakana_CV.pdf: $(TEX) $(BIB)
						latexmk -pdf chandrakana_CV.tex

clean:
			latexmk -C
			rm -f *.aux *.bbl *.blg *.log *.out *.vtc *.fls *.fdb_latexmk
