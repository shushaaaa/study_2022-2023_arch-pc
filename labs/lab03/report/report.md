---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Архитектура вычислительных машин"
author: "Норсоян Шушаник Гагиковна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
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
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.

# Задание

1. В соответствующем каталоге сделайте отчёт по лабораторной работе No 3
в формате Markdown. В качестве отчёта необходимо предоставить отчёты
в 3 форматах: pdf, docx и md.
2. Загрузите файлы на github.


# Выполнение лабораторной работы
1.Откроем терминал

2.Перейдем в каталог курса сформированный при выполнении лабораторной работы как на рисунке [-@fig:002]

![Переход в каталог курса](image/Рис1.png){ #fig:002 width=90% }

3.Перейдём в каталог с шаблоном отчета по лабораторной работе №4 как на рисунке [-@fig:003])

![Переход в каталог шаблона](image/Рис2.png){ #fig:003 width=90% }

4.Проведём компиляцию шаблона с использованием Makefile. Для этого введём команду make как на рисунке [-@fig:004]

![Компиляция шаблона](image/Рис3.png){ #fig:004 width=90% }

5.При успешной компиляции должны сгенерироваться файлы report.pdf и report.docx. Откроем и проверим корректность полученных файлов как на рисунке [-@fig:005]

![Корректность полученных файлов](image/Рис4.png){ #fig:005 width=90% }

6.Удалим полученные файлы с использованием Makefile. Для этого введём команду make clean как на рисунке [-@fig:006]

![Удаление полученных файлов](image/Рис5.png){ #fig:006 width=90% }


# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
