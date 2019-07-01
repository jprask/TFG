---
title:
  - Sistema de Recomendação Baseado em Confiança para Promover a Colaboração em Redes de Pesquisa Científica
author:
  - João Pedro R. D. Saldanha
  - Fernando Prass
institute:
  - Universidade Franciscana (UFN)
    - Ciencia da Computação
date:
  - Junho de 2019
    - TFG I
theme:
  - Antibes
aspectratio:
  - 169
header-includes:
  - \usepackage{mathtools}  
  - \usepackage{multirow}
toc: true
slide-level: 2
navigation: horizontal
# colortheme:
  # - frigatebird
#▶ pandoc presentation.md -t beamer -o pres.pdf
---


# Section

## This is our first section.

Another paragraph.

We can use Markdown for figures.

Markdown for lists

* One
* Two
    * Nested one
* Three
    1. Numerated list
    1. No need to specify number

We can even inline math: $y = ax + b$.  

# Slide

How about displayed equations:

$$
y = -2.2x + 0.5
$$
Just use Markdown to define sections and structure of the document.

Let's finish with a footnote.[^1]

[^1]: I'm a footnote!



pandoc -N --variable version=2.0 MANUAL.txt --toc -o example14.pdf
pandoc -N --variable version=2.0 presentation.md --toc beamer -o pres.pdf
