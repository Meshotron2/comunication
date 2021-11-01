all: pdf pptx

pdf:
	pandoc presentation.md \
		-so presentation.pdf \
		-t beamer \
		--slide-level=2 \
		--metadata-file=metadata.yml
pptx:
	pandoc presentation.md \
		-so presentation.pptx \
		--metadata-file=metadata.yml

