crop/01_iris_table.png: 01_iris_table.pdf
	pdfcrop $< $(@F).pdf
	convert -density 300 -trim $(@F).pdf -quality 100 $@
	rm $(@F).pdf

.PHONY: png

png: crop/01_iris_table.png
