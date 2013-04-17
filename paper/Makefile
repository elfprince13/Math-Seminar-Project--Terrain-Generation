all: terrain.bbl
	pdflatex terrain.tex
	pdflatex "Terrain Presentation.tex" 
terrain.bbl: terrain.aux
	bibtex terrain.aux

terrain.aux:
	pdflatex terrain.tex

clean:
	rm terrain.pdf
	rm terrain.log
	rm terrain.bbl
	rm terrain.blg
	rm terrain.aux
	rm "Terrain Presentation.aux"
	rm "Terrain Presentation.log"
	rm "Terrain Presentation.nav"
	rm "Terrain Presentation.out"
	rm "Terrain Presentation.pdf"
	rm "Terrain Presentation.snm"
	rm "Terrain Presentation.toc"
