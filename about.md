---
layout: page
title: Про предмет
description: Загальна інформація.
nav_order: 1
---

# Про предмет
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- Базовi знання з лiнiйної алгебри та теорiї ймовiрностей.
- Досвiд тренування нейронних мереж (iнiцiалiзацiя, оптимiзацiя, регуляризацiя, вибiр методу
та метрик для оцiнки).

Підручники
: 1. Sutton, R. S., & Barto, A. G. (2018). [*Reinforcement learning: An introduction.* ](http://incompleteideas.net/book/the-book-2nd.html) MIT press.
1. Zai, A., & Brown, B. (2020). [*Deep reinforcement learning in action.*](https://www.manning.com/books/deep-reinforcement-learning-in-action) Manning Publications.
1. Кочура Ю. П., Гордієнко Ю. Г. (2024). [*Нейронні мережі*](https://github.com/dml-book/dml/releases/download/v0.1.10/0.1.10-final.pdf).


## На випадок повітряної тривоги
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}