---
## Front matter
title: "Отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Мустафаев Заур Магомедович"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Теоретическое введение

Чтобы создать заголовок, используйте знак #.
Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:
This text is **bold**.
Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
This text is *italic*.
Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:
This is text is both ***bold and italic***.
Блоки цитирования создаются с помощью символа >:
> The drought had lasted now for ten million years, and the reign of the
terrible lizards had long since ended. Here on the Equator, in the
continent which would one day be known as Africa, the battle for existence
had reached a new climax of ferocity, and the victor was not yet in sight.
In this barren and desiccated land, only the small or the swift or the
fierce could flourish, or even hope to survive

# Выполнение лабораторной работы

1. Переход в каталог курса сформированный при выполнении лабораторной работы №2:
![Переход в каталог lab02](Рис. 2.1 Переход в каталог lab02.png){#fig:001 width=70%}

2. Обновите локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды
![Обновление репозитория](Рис. 2.2 Обновление репозитория.png){#fig:001 width=70%}

3. Перейдите в каталог с шаблоном отчета по лабораторной работе №3
![Переход в каталог lab03](Рис. 2.3 Переход в каталог lab03.png){#fig:001 width=70%}

4. Проведите компиляцию шаблона с использованием Makefile.Для этого введите команду.
![Компиляция шаблона](Рис. 2.4 Компиляция шаблона.png){#fig:001 width=70%}

5. При успешной компиляции должен сгенерироваться файл report.pdf и report.docx.Откройте и проверьте коррективность полученных файлов.
![Проверка правильности](2,5.png){#fig:001 width=70%}

6. Удалите полученный файлы.
![Удаление файлов](2,6.png){#fig:001 width=70%}

7. Откройте файл report.md с помощью любого текстового редактора, например gedit.
![Открытие файла](2,7.png){#fig:001 width=70%}

8. Заполните отчетность и скомпилируйте отчет с использованием Makefile.Проверьте корректность полученных файлов.
![Открытие файла](2,7,.png){#fig:001 width=70%}

# Выводы

В ходе выполнения лабораторной работы, я освоил процедуры оформления отчетов с помощью легковесного языка разметки MarkDown.

# Список литературы{.unnumbered}

::: {#refs}
:::
