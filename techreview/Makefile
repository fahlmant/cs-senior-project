TARGET=techreview
HTML=main_html

default: pdf

dvi: ${TARGET}.tex 
	latex ${TARGET}.tex
	bibtex ${TARGET}
	latex ${TARGET}.tex
	latex ${TARGET}.tex

ps: dvi
	dvips -R -Poutline -t letter ${TARGET}.dvi -o ${TARGET}.ps

pdf: ps
	ps2pdf ${TARGET}.ps

clean:
	rm *.log
	rm *.dvi
	rm *.ps
	rm *.aux
	rm *.bbl
	rm *.blg

cleanpdf:
	rm *.pdf
