---
title: Как редактировать
permalink: edit-ru
layout: info
published: true
---

## Ссылка «Редактировать»

Измени любую страницу, следуя по ссылке **Редактировать** вверху каждой страницы, и перейдя в редактор Prose.io. Внимание: для сохранения изменений нужен аккаунт [GitHub](https://github.com/join).

## Создай страницу

+ Перейди в [Редктор](http://prose.io/#indexmod/encyclopedia/edit/master/sandbox.md)

+ Найди `template.md` и скопируй содержимое

+ Во вкладке encyclopedia создай новый файл с расширением .md

+ Вклей содержимое `template.md` в новый файл

+ Отредактируй **Page title** и **Permalink** в верхней области файла отделённой тремя дефисами ---

## Написание статьи

Цель Индексмод энциклопедии упростить синтакс wiki для красивого и легкого вида статей. Далее несколко советов по аккуратному редактирванию.

## Markdown

Каждая страница создана с помшью [Markdown](https://daringfireball.net/projects/markdown/syntax) лёгкого и простого языка для создания статических страниц.

##  Front matter

Каждая страница имеет скрытую область с мета-данными. Эта область **Front matter** отделена тройными дефисами.

`---`
`title: How to edit`
`permalink: edit`
`layout: default`
`---`

Пример сверху это **Front matter** странцы с заголовком **How to edit**. Типичный **Front matter** может содержать **Page title**, **Permalink**, **Layout** и другие мета-данные.

## Структура страницы

Видимая часть страницы состоит из **Заголовка**, раздела **Основной**, **Картинки** с **Описанием** и **Кредитами**, раздела **Конспект**, разделов **См. также** м **Сноски**.

## Заголовок  

`# Aberdeen Fashion Week`
`# Tailor, Victoria`
`# Дума, Мирослава (издатель)`

Заголовок содержит название предмета статьи **Рынок Ями-Ичи**, фамилию и имя **Пугачева, Алла** и может быть дополнена уточнением **Рубчинский, Гоша (дизайнер)**.

## Основной раздел

`(Born 1968, Paris)`
`(Est. 2012, Moscow)`

Основной раздел начинается с уточнения в круглых скобках **(Род., Осн., 1999, город)** с указанием даты рождения, основания и горорда. После двух трех предложений Основной раздел заканчивается  ссылкой в раздел сноски с указанием сточника в **Квадратных скобках**. Пример

Код ниже

`<span id="a1">[\[1\]](#f1)</span>`

Будет показываться так

<span id="a1">[\[1\]](#f1)</span>

## Картинка. подпись и кредиты

Это ссылка картинки

![](/encyclopedia/images/image-name.jpg)

Это код для подписи под картинкой

`**Image caption**`

Отображается так

**Image caption**

Это код для кредитов к картинке

`*Фото: [Фотограф](name) / [Источник](link)*`

Будет показан так

*Фото: [Фотограф](name) / [Источник](link)*

Название или описание иллюстрации должно быть **жирным шрифтом**. Строка с кредитами начинается с **Имени фотографа** должна быть *курсивом* с [активной ссылкой](active-link.md) и после наклонного разделителя должен быть указан источник откуда взята фотография, и/или название издания. Ссылки могут указывать на еще **не созданные страницы** в энциклопедии c таким **фамилия-имя** и таким видом **название-издания** латиницей.

## Раздел «Конспект»

Используй шаблон этого раздела для представления любых структурированных списков и данных

`|Год|Город|`
`|---|---|`
`|2014|Токио|`
`|2015|Москва|`
`|2017|Париж|`

Будет показан как

|Year|City|
|----|-----|
|2014|Tokyo|
|2015|Moscow|
|2017|Paris|

## Раздел «См. также»

See also section connects your page with others pages in Indexmod Encyclopedia. Use following template combining list and link styling syntax. The code

`+ [See also](index)`

Will be rendered as

+ [See also](index)

## Раздел Ссылки

Code for footnote

`[[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)] (http://example.net/article)`

Will be rendered as

[[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)

Connect some text using short links <span id="a1">[\[1\]](#f1)</span>, <span id="a2">[\[2\]](#f2)</span>, <span id="a3">[\[3\]](#f3)</span> with links and source in **Footnote** edit. Kepp numbering in links organized: [[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)

## Prose.io editor

Every page may be edited in [Prose.io](www.prose.io) editor using link "Edit the "page name"" at top-left section of each page. To save  changes you may need have an account and be authorized as [GitHub](https://github.com/join) user.
