---
## Front matter
title: "2 этап реализации проекта"
subtitle: "Архитектура компьютеров и операционные системы"
author: "Дмитрий Константинович Кобзев"

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

## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

# Реализация проекта

Добавляем к сайту данные о себе (рис. [-@fig:001])

![Фотография владельца сайта, краткое описания владельца сайта, информация об интересах и информация об образовании](image/1.png){#fig:001 width=70%}

Делаем пост по прошедшей неделе (рис. [-@fig:002]), (рис. [-@fig:003]), (рис. [-@fig:004]), (рис. [-@fig:005])

![Пост по прошедшей неделе](image/2.png){#fig:002 width=70%}

![Пост по прошедшей неделе](image/3.png){#fig:003 width=70%}

![Пост по прошедшей неделе](image/4.png){#fig:004 width=70%}

![Пост по прошедшей неделе](image/5.png){#fig:005 width=70%}

Делаем пост Пост на тему CI/CD (рис. [-@fig:006]), (рис. [-@fig:007]), (рис. [-@fig:008]), (рис. [-@fig:009]), (рис. [-@fig:010])

![Пост на тему CI/CD](image/6.png){#fig:006 width=70%}

![Пост на тему CI/CD](image/7.png){#fig:007 width=70%}

![Пост на тему CI/CD](image/8.png){#fig:008 width=70%}

![Пост на тему CI/CD](image/9.png){#fig:009 width=70%}

![Пост на тему CI/CD](image/10.png){#fig:010 width=70%}
