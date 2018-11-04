all: slides.pdf
show: slides.pdf
	evince $<
slides.pdf: slides.md
	pandoc -t beamer $< -o $@
