---
## Front matter
title: "Лабораторная работа №11"
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

Приобрести навыки написания программ для работы с файлами.

# Задание

Здесь приводится описание задания в соответствии с рекомендациями
методического пособия и выданным вариантом.



# Выполнение лабораторной работы

Создаем каталог для программ лабораторной работы "№11 и соответствующие файлы (рис. [-@fig:001])

![Создание каталога и необходимых файлов](image/1.png){ #fig:001 width=70% }

Вводим файл 'lab11-1.asm' текста из листинга 11.1, далее создаем исполняемый файл и проверяем его работу (рис. [-@fig:002])

![Проверка работы файлов](image/2.png){ #fig:002 width=70% }

Изменяем права доступа к исполняемому файлу (запрещаем его выполнение) (рис. [-@fig:003])

![Изменяем права доступа к файлу](image/3.png){ #fig:003 width=70% }

Изменяем права доступа к 'lab11-1.asm', добавляя права на исполнение (рис. [-@fig:004])

![Права на исполнение и запуск файла](image/4.png){ #fig:004 width=70% }

В соответствии с вариантом предоставляем права доступа к 'readme.asm' (рис. [-@fig:005])

![Предоставляем права доступа](image/5.png){ #fig:005 width=70% }

Напишем программу, удовлетворяющую заданным условиям (рис. [-@fig:006])

![Программа](image/6.png){ #fig:006 width=70% }

Создаем исполняемый файл, выполняем программу, вводим в качестве аргумента свое имя и фамилию (рис. [-@fig:007])

![Выполнение программы](image/7.png){ #fig:007 width=70% }

Проверяем результат с помощью команды cat (рис. [-@fig:008])

![Проверка результата] (image/8.png){ #fig:008 width=70% }


# Выводы

В ходе выполнения данной лабораторной работы я приобрела необходимые навыки и смогла написать программу для работы с файлами.

# Список литературы{.unnumbered}

::: {#refs}
:::
