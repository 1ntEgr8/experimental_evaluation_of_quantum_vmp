.PHONY: pdf publish clean

pdf:
	latexmk -pdf -outdir=build main.tex

publish: pdf
	cp build/main.pdf .

clean:
	rm -rf build
