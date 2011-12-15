LaTeX preamble
==============

This is the preamble I use for writing semester reports. It has been developed during my time at Aalborg University, but is by no means perfect.
I depends on the [memoir package][memoir] and lots of other stuff, which should come standard with any recent [TeX Live][texlive] installation.
Source files are assumed to be UTF-8 encoding.

Structure
---------
* The main file is `main.tex`
* Content LaTeX files goes in `src`
* Images goes in `img`
* BibTeX sources goes in `sources.bib`
* Preamble stuff resides in `etc`. Take a look at `preamble.tex` to get an overview.

Features
--------
* Various [memoir][memoir] chapter styles
* Titling page, table of contents and bibliography
* Danish and English
* Source code listings
* TODO notes
* etc.

[memoir]:http://www.ctan.org/pkg/memoir
[texlive]:http://www.tug.org/texlive/

