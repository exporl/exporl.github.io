---
title: Thorough research of this special topic regarding the influence of various factors
author: [Author 1, Author 2]
biblio-files: parsed-references.bib
classoptions: DIV=14,twocolumn,fontsize=9pt
biboptions: doi=true
toc: true
toc-depth: 2
numbersections: true
numbersectionlevel: 2
knit: (function(input, encoding, make = TRUE) { source('templates/makefile-renderer.R', local = TRUE) })
---

%% smart
%% to=latex
%% template=templates/report.tex
%% filter=templates/paper-filters.py
%% biblatex



# Heading 1

## Heading 2

### Heading 3

<!-- Comments -->
Default lists:

- Citations [@Macherey2006] and inline, \eg @Macherey2006, references have a clickable link to Pubmed (articles) or Amazon (books)
- Standard abreviations \\eg and \\ie for \eg and \ie to get the spacing right.
- Some units like \pps{900}, look in the template to see which ones are available.
- **Highlights** and *highlights*.

## Unnumbered Heading {-}

Numbered lists:

1.  First paragraph
2.  Second paragraph
3.  Third paragraph

    Continued paragraphs

##### easy margin notes
Inlined lists:
[ipe]
\item Aenean faucibus.
\item Morbi dolor nulla, malesuada eu, pulvinar at, mollis ac, nulla.
\item Curabitur auctor semper nulla.
[/ipe]

##### *invisible heading

See *man pandoc_markdown* for more information.

![iris data](paper-r-example-figures/iris-1.pdf) 

![*iris data spanning columns](paper-r-example-figures/iris-wide-1.pdf) 
