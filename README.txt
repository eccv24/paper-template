To make a sample ECCV paper, copy the contents of this directory
somewhere, and type

 pdflatex main
 bibtex main
 pdflatex main
 pdflatex main

or 

latex main
bibtex main
latex main
latex main
dvips main
pstopdf main.ps