# K suboru: proj3.tex
# Datum:    4.4.2024
# Autor:    Valentyn Vorobec (xvorob02@stud.fit.vutbr.cz)
# Projekt:  ITY projekt 3

PROJ=proj3

$(PROJ).pdf: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out

clean-all: clean
	rm -f $(PROJ).pdf
