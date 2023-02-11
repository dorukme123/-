---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Лабораторная работа № 1"
author: "Мерич Дорук Каймакджыоглу"

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
Изучить основы разметки markdown. Подготовить рабочее пространство. Привыкать работать с удаленным репозиторием Git в Виндовсе.


# Задание
Выполнить лабораторный отчет и выполнить необходимые задачи и подготить отчет по лабораторной работе по дисциплине Математическое моделирование.
Выдать отчет о работе в соответствии с существующим шаблоном работы.


# Теоретическое введение
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/git.png"/>
Git -- это инструмент DevOps, используемый для управления исходным кодом. Это бесплатная система контроля версий с открытым исходным кодом, используемая для эффективной обработки небольших и очень крупных проектов. Git используется для отслеживания изменений в исходном коде, позволяя нескольким разработчикам совместно работать над нелинейной разработкой.
Github -- это платформа для размещения кода для контроля версий и совместной работы. Это позволяет вам и другим пользователям совместно работать над проектами из любой точки мира. В этом руководстве вы познакомитесь с основами GitHub, такими как репозитории, ветви, коммиты и запросы на извлечение.


# Выполнение лабораторной работы

1. я открыл новый репозиторий под названием math-modeling. клонировал репозиторий примера в мою папку git и добавил его в мой git, затем зафиксировал репозиторий. в последний раз я поместил его в свой github в главной ветке.
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/1.jpg"/>

2. я выполнил основные шаги в моем git bash. создал index.html и зафиксировал это с помощью кода, который приведен в лабораторном отчете.
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/1.2.jpg"/>
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/1.2code.jpg"/>

3. я составил лабораторный отчет и снял видео, как я это делаю, и опубликовал на YouTube в 2 частях.
[part1](https://youtu.be/gfyv3sH8NGs)
<br>
[part2](https://youtu.be/U3f0F7_YXPM)
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/video.jpg"/>

4. поместил все изменения в репозиторий с окончательным отчетом.
<img src="https://github.com/dorukme123/math-modelling/tree/main/labs/lab01/report/report/image/push.jpg"/>


# Выводы

Создал рабочую область и создал репозиторий. Основные команды Git и синтаксис markdown были изучены.

# Список литературы{.unnumbered}

[github](https://github.com) {#refs:git}
<br>
[git](https://git-scm.com) {#refs:github}
