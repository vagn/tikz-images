
%.pdf: %.tex
	pdflatex $<

targets := r.pdf

default: $(targets)
	atril $(targets)

clean:
	rm -f *.aux *.log *.pdf

realclean: clean
