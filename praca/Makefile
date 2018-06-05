all:
	mkdir -p build
	pdflatex -shell-escape -halt-on-error -output-directory build praca.tex
	makeglossaries -d build praca 
	pdflatex -shell-escape -halt-on-error -output-directory build praca.tex

clean:
	rm -rf build
