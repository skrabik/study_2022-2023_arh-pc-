---
## Front matter
title: "Отчёт по лабораторной работе номер 4"
subtitle: "Язык разметки Markdown"
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

Научиться оформлять отчеты с помощью легковесного языка разметки Markdown



# Выполнение лабораторной работы

Перейдём в каталог курса, обновим локарьный репозиторий. Перейдём в каталог с шаблоном отчёта по лабораторной работе номер 4. Проводим компиляцию шаблона с использованием Makefile. (Рисунок 1)

Рисунок 1(image/Снимок экрана от 2022-10-27 10-50-19.png){ #fig:001 width=70% }

Удаляем полученные файлы (Рис 1)

Рисунок 2(image/Снимок экрана от 2022-10-27 10-50-55.png){ #fig:001 width=70% }

Проверяем, что после этой команды файлы report.pdf и report.docx были удлены. (Рис 3)

Рисунок 3(image/Снимок экрана от 2022-10-27 10-51-24.png){ #fig:001 width=70% }

Далее открываем этот файл с помощью текстового редактора и заполняем данный отчёт.

После загружаем файлы на Github.
 
# Выводы

В результате выполнения лабораторной работы я освойл процедуру оформления отчетов с помощью Markdown


