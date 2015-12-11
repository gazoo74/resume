# How compile my LaTeX resume
First you will need to install *LaTeX*, *pdflatex*, *epstopdf* and *Mordern CV* onto you system. Follow instructions from [prerequisite](#prerequisite) or go directly to the [compile](#compile) section.
## [Prerequisite](#=prerequisite)
This will install LaTeX for Fedora:
```
sudo yum install -y latexila texlive-latex-bin texlive-moderncv texlive-epstopdf-bin texlive-babel-french
sudo texhash
```
## [Compile](#=compile)
Simply run...
```
make english.pdf
```
or
```
pdflatex english.tex
```
... voilà! my resume is available under *[english.pdf](pdf/english.pdf)*.

Enjoy!

PS: Check also *[french.pdf](pdf/french.pdf)* and *[french-short.pdf](pdf/french-short.pdf)*.
