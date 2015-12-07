prefix=cv
pdfreader=open
all: $(prefix).pdf
$(prefix).pdf: $(prefix).tex
	xelatex $(prefix).tex
	$(pdfreader) $(prefix).pdf &
run:
	$(pdfreader) $(prefix).pdf &
clean:
	rm $(prefix).pdf
