# K suboru: proj5.tex
# Projekt:  ITY projekt 5

PROJ=proj5

$(PROJ).pdf: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	pdflatex $(PROJ).tex
	pdflatex $(PROJ).tex
	dvips $(PROJ).dvi
	ps2pdf $(PROJ).ps

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out

clean-all: clean
	rm -f $(PROJ).pdf
