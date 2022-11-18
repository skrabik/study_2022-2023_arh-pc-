---
## Front matter
title: "Отчёт по лабораторной работе %6"
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

Приобрести практические навыки работы в Midnight Commander. Освоить
инструкции языка ассемблера mov и int.

# Выполнение лабораторной работы

Открываем Midnight Comander и переходим в нужный каталог (рис. [-@fig:001])

![Открываем Midnight Comander](image/1.png){ #fig:001 width=70% }

Создаём дирректорию lab06 и файл lab6-1.asm (рис. [-@fig:002])

![Создание файла](image/2.png){ #fig:002 width=70% }

Вводим текст программы из листинга 6.1, сохраняем изменения и закрываем файл  (рис. [-@fig:003])

![Записывам программу в файл](image/3.png){ #fig:003 width=70% }

Убеждаемся, что файл содерит текст программы (рис. [-@fig:004])

![Проверка файла](image/4.png){ #fig:004 width=70% }

Оттранслируем текст программы в объектный файл и выполняем компановку. Запускаем исполняемый файл. На запрос вводим ФИО(ribabenko). (рис. [-@fig:005])

![Выполняем программу](image/5.png){ #fig:005 width=70% }

Скачиваем файл 'in_out.asm'и копируем его в каталог, в котором лежит файл с программой. (рис. [-@fig:006])

![копирование 'in_out.asm'](image/6.png){ #fig:006 width=70% }

Создаём копию lab6-1 и записываем в неё листинг 6.2. (рис. [-@fig:007])

![Создание второго файла](image/7.png){ #fig:007 width=70% }

Проверяем работу второго файла. (заменили sprintLF на sprint) При второй команде ввод текста происходит именно в данную строку.(рис. [-@fig:008])

![Проверяем работу второго файла.](image/8.png){ #fig:008 width=70% }

#Задания для самостоятельной работы

Создаём копию первого файла и вносим изменения в программу (добавляем вывод). (рис. [-@fig:009])

![Вносим изменения в копию первого файла](image/9.png){ #fig:009 width=70% }

Проверяем работоспособность программы (рис. [-@fig:010])

![Проверка вывода](image/10.png){ #fig:010 width=70% }

Создаём копию второго файла и вносим изменения в программу (добавляем вывод с ипрользованием внешнего файла). (рис. [-@fig:011])

![Вносим изменения в копию второго файла](image/11.png){ #fig:011 width=70% }

Проверка вывода (рис. [-@fig:012])

![Проверка второго файла](image/12.png){ #fig:012 width=70% }


# Выводы

В ходе выполнения данной лабораторной работы я приобрёл практические навыки работы в Midnight Commander и освоил инструкции языка ассемблера mov и int.
