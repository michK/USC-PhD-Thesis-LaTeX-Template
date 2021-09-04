# USC-PhD-Thesis-LaTeX-Template
## A LaTeX template that conforms to the University of Southern California PhD thesis guidelines with nice default stylistic elements

This template should be a good starting point for a USC PhD thesis. The template should conform to all USC requirements, but since the requirements leave some room for stylistic choices,
the template includes a few stylistic elements relating to things like paragraph indentation, line spacing in the front matter, right-hand-side margin overflow etc.

For best results building LaTeX documents, I suggest using [latexmk](https://www.ctan.org/pkg/latexmk/). Once it's installed, build the document with
`latexmk -pdf USC-PhD.tex`

Using `latexmk` ensures that all required build sequences are run so that cross-referencing and bibliography entries are up to date.
For intermediate testing, `pdflatex USC-PhD.tex` will be a bit faster, but if you find that some references are not updating, use `latexmk`.

It is possible that the nomenclature will not appear initially, and if that is the case run

`makeindex <filename>.nlo -s nomencl.ist -o <filename>.nls`

and try again.

### Pull requests and issue submissions are welcome.

### Disclaimer: This is not an official USC template
