---
## Front matter
title: "Лабораторная работа №8"
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

Цель данной работы: изучить команды условного и безусловного перехода, приобрести навыки написания программ с использованием перехода, познакомиться с назначением и структурой файла листинга.




# Выполнение лабораторной работы

Создаем каталог для программ лабораторной работы №8, переходим в него и создаем файл lab8-1.asm (рис. [-@fig:001])

![Создание каталога и файла](image/1.png){ #fig:001 width=70% }

Введем в файл lab8-1.asm текст программы из листинга 8.1 (рис. [-@fig:002])

![Текст программы из листинга 8.1](image/2.png){ #fig:002 width=70% }

Создаем исполняемый файл и запускаем его. (рис. [-@fig:003])

![Создание исполняемого файла](image/3.png){ #fig:003 width=70% }

Далее в текст программы после вывода сообщения №2 добавим инструкцию jmp с меткой _label1 и после вывода сообщения №1 добавим инструкцию jmp с меткой _end. Изменим текст программы в соответствии с листингом 8.2 (рис. [-@fig:004])

![Изменяем текст программы в соответствии с листингом 8.2](image/4.png){ #fig:004 width=70% }

Создаем исполняемый файл и проверяем его работу (рис. [-@fig:005])

![Создание исполняемого файла](image/5.png){ #fig:005 width=70% }

Изменим текст программы, добавив и изменив инструкцию jmp, чтобы сообщения выводились с 3-го по 1-ый (рис. [-@fig:006])

![Текст измененной программы](image/6.png){ #fig:006 width=70% }

Создаем исполняемый файл и проверяем его работу (рис. [-@fig:007])

![Создание исполняемого файла](image/7.png){ #fig:007 width=70% }

Создаем файл lab8-2.asm, вводим в него текст программы из листинга 8.3 (рис. [-@fig:008])

![Текст программы из листинга 8.3](image/8.png){ #fig:008 width=70% }

Создаем исполняемый файл и проверяем его (рис. [-@fig:009])

![Создание исполняемого файла](image/9.png){ #fig:009 width=70% }

Далее создаем файл листинга для программы из файла д=lab8-2.asm (рис. [-@fig:0010])

![Создание файла листинга](image/10.png){ #fig:0010 width=70% }

Открываем файл листинга с помощью текстового редактора mcedit (рис. [-@fig:0011])

![Открытие файла листинга](image/11.png){ #fig:0011 width=70% }

Открываем файл с программой lab8-2.asm и на строке 39 удаляем операнд. Выполняем трансляции с получением файла листинга (рис. [-@fig:0012])

![Трансляция файла листинга с удалением операнда на 42 строке](image/12.png){ #fig:0012 width=70% }

Открываем текстовый редактор mcedit (рис. [-@fig:0013])

![Текстовый редактор mcedit](image/13.png){ #fig:0013 width=70% }

Задание для самостоятельной работы. 1 задание. Следует написать программу, которая из трех целочисленных переменных находит наименьшее. (рис. [-@fig:0014])

![Программа для нахождения наименьшей переменной (1)](image/14.png){ #fig:0014 width=70% }

Текст программы задания №1 (рис. [-@fig:0015])

![Программа для нахождения наименьшей переменной (2)](image/15.png){ #fig:0015 width=70% }

Создаем исполняемый файл и проверяем его. У меня был вариант-20, значит вывести программа должна была цифру 2, но она вывела 50, что в таблице ASCII соответствует символу "2" (рис. [-@fig:0016])

![Создание исполняемого файла](image/16.png){ #fig:0016 width=70% }

2 задание. Необходимо написать программу, которая для введенных с клавиатуры значений х и а вычисляет значение заданной функции f(x) и выводит результат вычислений.  (рис. [-@fig:0017])

![Текст программы задания 2 (1)](image/17.png){ #fig:0017 width=70% }

Продолжение программы (рис. [-@fig:0018])

![Текст программы задания 2 (2)](image/18.png){ #fig:0018 width=70% }

Создаем исполняемый файл и проверяем его (рис. [-@fig:0019])

![Создание исполняемого файла](image/19.png){ #fig:0019 width=70% }

# Выводы

В ходе данной лабораторной работы я изучила команды условного и безусловного перехода, приобрела навыки написания программ с использованием перехода, познакомилась с назначением и структурой файла листинга.

# Список литературы{.unnumbered}

::: {#refs}
:::
