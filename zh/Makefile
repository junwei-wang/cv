prefix=resume-zh
all: $(prefix).pdf
$(prefix).pdf: $(prefix).tex resume.bib
	xelatex $(prefix).tex
	bibtex $(prefix)
	xelatex $(prefix).tex
	xelatex $(prefix).tex
	open $(prefix).pdf &
run:
	open $(prefix).pdf &
clean:
	rm $(prefix).pdf
