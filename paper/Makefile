all: terrain.bbl
	latex terrain.tex
	dvipdfm terrain.dvi

terrain.bbl: terrain.aux
	bibtex terrain.aux

terrain.aux:
	latex terrain.tex

clean:
	rm terrain.dvi
	rm terrain.pdf
	rm terrain.log
	rm terrain.bbl
	rm terrain.blg
	rm terrain.aux
