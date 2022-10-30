---
## Front matter
title: "Отчет по лабораторной работе №4"
subtitle: "Дисциплина: Архитектура компьютера"
author: "Ким Ангелина Павловна"

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

В ходе данной лабораторной работы нужно освоить процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы

Перезодим в каталог курса  сформированный при выполнении лабораторной работы №3, далее обновляем репозиторий. Следующим шагом переходим в каталог с шаблоном отчета по лабораторной работе №4. Далее проводим компиляцию шаблона с использованием Makefile.  (рис. [-@fig:hey])

![Переход в каталог курса](image/4.jpg){ #fig:hey width=70% }

Далее удаляем полученный файлы с использованием Makefile. (рис. [-@fig:ggg])

![Удаляем полученный файлы](image/2.jpg){ #fig:ggg width=70% }

Проверяем, что после этой команды файлы были удалены. (рис. [-@fig:fiii])

![Проверка удаленных файлов](image/3.jpg){ #fig:fiii width=70% }

Заполняем этот отчет и загружаем его на github.

# Выводы

Я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.



