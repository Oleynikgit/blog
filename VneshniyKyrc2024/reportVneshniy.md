## Front matter
title: "Внешний курс"
subtitle: "Основы информационной безопасности"
author: "Олейник Артём Александрович"

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
lot: false # List of tables
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

## Содержание

# 1	Цель работы
•	Пройти курс
•	Воспользоваться старым сайтом на hugo и добавить туда информацию о прохождении курса
# 2	Задание
    1. Пройти курс на stepik;
    2. Получить скриншот с выполнением на степике;
    3. Загрузить скриншот на личный сайт hugo;
    4. Обновить информацию на github;
# 3	Теоретическое введение
Нужно пройти курс на stepik,вся нужная информация для успешного прохождения содержится в видео и лекциях(они идут в пдф формате,что очень удобно,можно пользоваться поиском по слову).
# 4	Выполнение лабораторной работы
    1. Войти на stepik,и ВНИМАТЕЛЬНО изучить материалы к курсу,чтобы "не тыкать пальцем в небо" при выборе ответа.
    2.Успешно пройти курс используя материалы на сайте,и получить заветный "сертификат" о прохождении.
    3.Найти папку со своим сайтом из прошлого курса,если не получилось,скачать с гитхаба куда выкладывали.
    4.Отредактировать сайт(с этим проблем абсолютно не возникает,старые лекции в помощь)
    5.Обновить информацию на гитхабе: Выложить актуальный сайт,добавить папку с проектом и скриншоты
# 5	Выводы
Вспомнил,как редактировать hugo сайт,узнал много нового про фишинг, и почему так важно подбирать надежный пароль,узнал,про криптовалюту и появились знания блокчейна.Курс крайне интересный и информативный,но маленький.

# Список литературы
1. 	Старые лекции по Hugo Кулябова Дмитрия Сергеевича.
2. 	Курс https://stepik.org/lesson/666230/step/6?unit=664219
3. 	Шаблон отчета Дарья Беличева: https://github.com/dmbelicheva/study_2022-2023_sciprog-intro/blob/master/labs/lab1/report/report.docx
