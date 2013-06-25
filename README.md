This GitHub repository is being used to draft a scientific manuscript
to describe FALDO, a formal ontology for Feature Annotation Locations
in RDF: https://github.com/JervenBolleman/FALDO

FALDO was begun at the BioHackathon 2012 meeting in Japan,
https://github.com/dbcls/bh12/wiki/Feature-annotation-locations-in-RDF

We are currently writing the manuscript using LaTex using a BMC journal
template (files named `bmc_article.*`) with `location.tex` as the
primary file which includes the sub-sections as separate child files:

 * `abstract.tex` - Abstract
 * `background.tex` - Background
 * `implementation.tex` - Implementation
 * `results.tex` - Results
 * `discussion.tex` - Discussion
 * `conclusions.tex` - Conclusions
 * `avareq.tex` - Availability and requirements

To produce the whole PDF file, use LaTeX and BibTex:

    $ pdflatex location.tex
    $ bibtex location
    $ pdflatex location.tex
