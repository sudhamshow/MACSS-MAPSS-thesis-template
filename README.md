# University of Chicago M.A Thesis Template (for Social Science programs) in Rmarkdown

This is a rendition of a template for the University of Chicago M.A thesis and thesis proposal. Some of the templates may be specific to the Department of Sociology, but can be modifiable to your needs. Verify if the format of the title page is as required before uploading your thesis in the University library. They seldom ask you to resubmit it if not in the required format. This repository has the titlepage requirements for 2023.

## Dependencies

In order to render the ```thesis.Rmd``` or ```proposal.rmd``` file 'out of the box' you need to have 
the following R packages installed:

- dplyr
- ggplot2
- xtable
- [lingStuff](http://www.jvcasillas.com/lingStuff/) (installation instructions available in the link)

## Quick Start Guide

Edit the title page in [doc_prefix.tex](/includes/tex/doc_prefix.tex). Add Acknowledgements, Abstract and new chapters in the files in the [sections](/sections) folder. Add images in the [figures](/includes/figures) folder. **Pro Tip** - Professional LLMs come handy in converting your citations to bib entry.

## Issues

- [ ] Knitr captions
	- [ ] include captions from knitr call
	- [ ] include figure in LOF from knitr call

---

## Acknowledgements

This template greatly borrows from the 
heavy lifting was done by colleagues at the University of Arizona. The fork for the University of Chicago template originated from the repository by [jvcasill](https://github.com/jvcasill/ua_thesis_rmd) who worked to make the prior work at Arizona function nicely with `knitr`.
