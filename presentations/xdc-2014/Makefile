.PHONY: all clean

all: presentation.pdf

presentation.pdf: presentation.tex freebsd-logo.png
	pdflatex presentation.tex
	pdflatex presentation.tex

clean:
	rm -f \
		presentation.aux presentation.log presentation.nav \
		presentation.out presentation.pdf presentation.snm \
		presentation.toc
