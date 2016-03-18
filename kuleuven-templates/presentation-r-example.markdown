---
title: Thorough research of this special topic regarding the influence of various factors
subtitle: Yeah we did it!
author: [Author 1, Author 2]
date: Date of presentation
institute: Institute, Dept., University
biblio-files: parsed-references.bib
toc: true
sectiontoc: true
sectiontitle: true
captionfont: size=\scriptsize
# customization of the templates
header-includes: \input{presentation-example.header}
knit: (function(input, encoding, make = TRUE) { source('templates/makefile-renderer.R', local = TRUE) })
---

%% smart
%% to=beamer
%% slide-level 3
%% template=templates/presentation.tex
%% filter=templates/presentation-filters.py
%% biblatex



# Introduction

### Introduction Slide 1

![<1|handout:0><2>{f}](presentation-examplefig,presentation-examplefig-magenta)

<!-- Comments -->
Default lists:

- Citations [@Macherey2006] and @Macherey2006
- references have a clickable link to Pubmed or Amazon
- Standard abreviations \\eg and \\ie for \eg and \ie
- Units like \pps{900}
- **Highlights** and *highlights*

# Methods

# Results

## Part 1

[smallfooter]

### Results Slide 1

- You can replace the footer by a minimal version

[largefooter]

# Figure Examples

### Full Screen

- You can show full-screen figures as on the next slide

![{s}](presentation-examplefig-electrodes)

[largefooter]

### Fill Vertical

![{v}](presentation-examplefig-electrodes)

### Without Caption

[columns=2]

[column]

![]({h}presentation-examplefig-electrodes)

[column]

![{h}](presentation-examplefig-electrodes)

[/columns]

### Animated

[columns=2]

[column]

![<1|handout:0><2>]({f}presentation-examplefig-electrodes,{f}presentation-examplefig-electrodes-ref)

[column]

![<1|handout:0><2>{f}](presentation-examplefig-electrodes,presentation-examplefig-electrodes-ref)

[/columns]

### Animated 2

[columns=2]

[column]

![<1|handout:0><2>{f}](presentation-examplefig-electrodes)
![<1|handout:0><2>{f}](presentation-examplefig-electrodes-ref)

[column]

![<1|handout:0><2>iris data](presentation-r-example-figures/iris-1.pdf)![<1|handout:0><2>iris data](presentation-r-example-figures/iris-2.pdf)

[/columns]

### With Caption

[columns=2]

[column]

![The 10-20 system]({width=\textwidth}presentation-examplefig-electrodes)

[column]

![{width=\textwidth}The 10-20 system](presentation-examplefig-electrodes)

[/columns]

# Conclusions

[notoc]

[nosupertitle]

### Conclusions

Numbered lists:

1.  First paragraph \pause
2.  Second paragraph
3.  Third paragraph

    Continued paragraphs

<!-- vi: set spell spelllang=en linebreak et nolist showbreak=>\ \ \  : -->
