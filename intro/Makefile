engine = latexmk -pdf -shell-escape -verbose -file-line-error -interaction=nonstopmode
file = intro

.PHONY: clean

all:
	$(engine) $(file)

clean:
	rm -f *.aux *.bbl *.bcf *.blg *.log *.out *.run.xml *.toc *.nav *.snm *.synctex.gz-current;
	rm -f *.synctex.gz *_vimtex.* *.fls *.fdb_latexmk *.pdf;
	rm -rf _minted-$(file)*;
	rm -f *.vrb *pyg

