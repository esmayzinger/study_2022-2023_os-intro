---
## Front matter
title: "индивидуальный проект: этап 1"
subtitle: "этап 1"
author: "Майзингер Эллина Сергеевна"

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

Разместить на Github pages заготовки для персонального сайта.

# Задание
1. Установка необходимое программное обеспечение.
2. Разместить его на хостинге git.
3. Установить параметр URLs сайта.
4. Разместить заготовку сайта на Github pages


# Теоретическое введение

# Выполнение лабораторной работы

## Установка hugo
С данного нам сайта устанавливаем hugo, разархивируем файлы и создадим папку bin в домашнем каталоге и добавим туда файл hugo (рис. @fig:001).

![файл hugo](image/04.png){#fig:001 width=70%}

## Клонирование репозитория 

Далее переходим в гитхаб, добавляем себе новый репозиторий, называем его blog6 (рис. @fig:002).


![добавляем новый репозиторий](image/05.png){#fig:002 width=70%}

С помощью команды git clone --recursive(ссылка) клонируем репозиторий на нашу виртуальную машину (рис. @fig:003).

![клонированный репозиторий](image/06.png){#fig:003 width=70%}

## Все идет не по плану 

В общем, пыталась я все это настроить, устанавливала hugo через терминал, только чего не устанавливала, но ничего не работало :( 
Вот можете посмотреть сколько я команд выполняла (рис. @fig:004) и (рис. @fig:005).

![история терминала](image/01.png){#fig:004 width=70%}

![история терминала](image/02.png){#fig:005 width=70%}


но всегда была одна и та же ошибка  (рис. @fig:006).

![история терминала](image/03.png){#fig:006 width=70%}


# Выводы

Итого три потраченных в пустую дня :(

# Список литературы{.unnumbered}
     

