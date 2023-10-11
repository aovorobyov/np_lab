---
# Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Введение в работу с Octave"
author: "Александр Олегович Воробьев"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы  

Приобрести практические навыки работы в Octave.

# Выполнение лабораторной работы  

**1. Простейшие операции.**  

![Простейшие операции](screens/1.png){ #fig:001 width=70% }  

**2. Операции с векторами**  

![Операции с векторами](screens/2.png){ #fig:002 width=70% }  

**3. Вычисление проектора**  

![Вычисление проектора](screens/3.png){ #fig:003 width=70% }  

**4. Матричные операции**  

![Матричные операции](screens/4.png){ #fig:004 width=70% }  

**5. Построение простейших графиков**  

![Построение простейших графиков 1](screens/5.png){ #fig:005 width=70% }  

![Построение простейших графиков 2](screens/6.png){ #fig:006 width=70% }  

**6. Два графика на одном чертеже**  


![Два графика на одном чертеже](screens/7.png){ #fig:007 width=70% }  

**7. График $y = x^2 sin (x)$**  

![График функции](screens/8.png){ #fig:008 width=70% }  

**8. Сравнение циклов и операций с векторами**  

![Сравнение циклов и операций с векторами](screens/9.png){ #fig:009 width=70% }  


# Выводы  
  
Приобрел практические навыки работы в Octave.

# Список литературы{.unnumbered}  

	1. Кулябов Д.С. Лабораторная работа No 3. Введение в работу с Octave - 9 с.

::: {#refs}
:::
