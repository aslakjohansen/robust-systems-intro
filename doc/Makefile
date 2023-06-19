TARGETS = \
	robust-systems-intro.pdf \


all: ${TARGETS}

clean:
	touch ${TARGETS}
	rm    ${TARGETS}

mrproper: clean
	touch d~ d.aux d.bbl d.bcf d.blg d.run.xml d.lof d.log d.out d.toc d.idx d.ilg d.ind d.pyg d.nav d.vrb d.snm
	rm    *~ *.aux *.bbl *.bcf *.blg *.run.xml *.lof *.log *.out *.toc *.idx *.ilg *.ind *.pyg *.nav *.vrb *.snm


robust-systems-intro.pdf: robust-systems-intro.tex
	xelatex -shell-escape robust-systems-intro.tex
