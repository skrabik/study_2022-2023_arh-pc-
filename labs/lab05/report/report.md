---
## Front matter
title: "Лабораторная работа номер 5"
subtitle: "Дисциплина: Архитектура компьютеров"
author: "Бабенко Роман Игоревич"

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

Научиться компилировать и собирать программы, написанные на ассемблере NASM.

# Выполнение лабораторной работы

Создаём каталог, переходим в него и создаём текстовый файл hello.asm. (рис. [-@fig:001])

![Создиние текстового файла](image/1.png){ #fig:001 width=70% }

Открываем его и вводим следующий текст. (рис. [-@fig:002])

![Копируем текст](image/2.png){ #fig:002 width=70% }

Компилируем код и проверяем что создан файл hello.o. (рис. [-@fig:003])

![Компилируем код](image/3.png){ #fig:003 width=70% }

Компилируем исходный файл в obj.o и проверяем его наличие. (рис. [-@fig:004])

![компилируем файл в 'obj.o'](image/4.png){ #fig:004 width=70% }

Передаём объектный файл на обработку компановщику и  проверяем с помощью ls его наличие. (рис. [-@fig:005])

![Обрабатываем компановщиком](image/5.png){ #fig:005 width=70% }

Выполняем следующую команду. Файл будет иметь имя 'main', он был создан из файла 'obj.o'. (рис. [-@fig:006])

![Выполнение предложенной команды](image/6.png){ #fig:006 width=70% }

Запускаем на выполнение исполняемый файл. (рис. [-@fig:007])

![Запускаем файл](image/7.png){ #fig:007 width=70% }

# Задания для самостоятельной работы

Копируем hello.asm и lab05.asm в 'lab05'. (рис. [-@fig:008])

![Копируем файлы](image/8.png){ #fig:008 width=70% }

Изменяем файл lab05.asm. Оттранслируем текст в объектный файл. Выполняем компановку и запускаем исполняемый файл. (рис. [-@fig:009])

![Выполняем компановку и запускаем исполняемый файл](image/9.png){ #fig:009 width=70% }

Копируем файлы в локальный репозиторий. (рис. [-@fig:010]) (рис. [-@fig:011])

![Копируем файлы](image/10.png){ #fig:010 width=70% }

![Проверяем их наличие](image/11.png){ #fig:011 width=70% }

Загружаем файлы на github. (рис. [-@fig:012])

![Загружаем на github](image/12.png){ #fig:012 width=70% }

# Выводы

Я научился компилировать и собирать команды на NASM.

