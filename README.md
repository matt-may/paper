# Project paper

## Overview

* `template.tex` is the main TeX file. 
* `template.bib` is the BiBTeX references file. If you would like to add a reference, just append your reference to this file. You can find the BibTeX format for a given paper by doing a Google Scholar search for it, and then clicking `Import into BibTex`.
* To compile your file and view it, you can run this command (assuming you have `pdflatex` installed): `latex template; bibtex template; latex template; pdflatex template; open template.pdf`

## Contributing

1. Fork the repository via the button above.
1. git clone the forked repository on your local machine, e.g., `git clone git@github.com:<your_username>/paper.git`
1. Create a new branch, e.g., `git checkout -b new_references`
1. Commit some changes: `git commit -m "Added references"`
1. Once finished, push your new branch to Github: `git push origin new_references`
1. Create a pull request against the main repository.

More information: https://help.github.com/articles/using-pull-requests/
