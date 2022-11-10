---
## Front matter
title: "Отчет по лабораторной работе №5"
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

Освоение процедуры компиляции и сборки программ, написанных на ассем-
блере NASM.


# Выполнение лабораторной работы

Создаем каталог для работы с программами на языке ассемблера NASM (рис. [-@fig:001])

![Создание каталога](image/1.jpg){ #fig:001 width=70% }

Создаем текстовый файл с именем hello.asm (рис. [-@fig:002])

![Создаем текстовый файл](image/2.jpg){ #fig:002 width=70% }

Компилируем исходный файл hello.asm в obj.o (рис. [-@fig:003])

![Компиляция](image/3.jpg){ #fig:003 width=70% }

Объектный файл передаем на обработку компоновщику (рис. [-@fig:004])

![Обработка](image/4.jpg){ #fig:004 width=70% }

Задания самостоятельной работы. Создаем копию файла hello.asm с именем lab5.asm (рис. [-@fig:006])

![Копируем](image/6.jpg){ #fig:006 width=70% }

Вносим изменения в текст программы в файле lab5.asm (рис. [-@fig:007])

![Изменения в тексте программы](image/7.jpg){ #fig:007 width=70% }

Оттранслируем полученный текст программы lab5.asm в объектный файл. Выполняем компоновку объектного файла и запускаем получившийся исполняемый файл. (рис. [-@fig:008])

![Оттранслируем текст и выполним компоновку](image/8.jpg){ #fig:008 width=70% }

Скопируем файлы в локальный репозиторий (рис. [-@fig:009])

![Копируем файлы в локальный репозиторий](image/9.jpg){ #fig:009 width=70% }

Отправим файлы на github (рис. [-@fig:0010])

![Отправка на github](image/10.jpg){ #fig:0010 width=70% }

# Выводы

В ходе данной лабораторной работы я освоила основные процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Список литературы{.unnumbered}

::: {#refs}
:::
