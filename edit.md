---
title: How to edit
permalink: edit
layout: default
published: true
---
# Link on the top-left 

Edit any page following link on top-left section: you may edit every page with Prose.io editor using link "Edit the "page name"" at top-left section of each page. To save  changes you may need authorize as [GitHub](https://github.com/join) user.


# Create new pages from Template

Just go to [Template](template) copy it and paste in to new empty .md file. 

# Charachter by charachter 

The aim of Indexmod Encyclopedia to simplify wiki syntax for a pretty and light format. Following checklist explains few steps of creating and editing beautiful articles in Indexmod Encyclopedia.

# Markdown

Every page is written with [Markdown](https://daringfireball.net/projects/markdown/syntax) lightest and easiest language for static pages generating.

#  A Front matter

Each page on top have spacial are with meta data. This invisible **front matter** area is set with triple-dashed lines.

`---`
`title: How to edit`
`permalink: edit`
`layout: default`
`---`

Above code is a **front matter** of this page **How to edit**. Any **front matter** may contain **page title**, **permalink**, **layout** and other metadata.

# Page structure

The visible area of the page have **Title** and **Front** section, an image with **caption** and **credits**, **Conspectus** section, **See also** section and **Footnotes** section.

# Title  

`# Aberdeen Fashion Week`
`# Tailor, Victoria`
`# Duma, Miroslava (publisher)`


Title includes the subject's name **Aberdeen Fashion Week**, surname and name **Tailor, Victoria** and may be added with specification with round brackets **Tailor, Victoria (designer)**.

# Front

`(Born 1968, Paris)`
`(Est. 2012, Moscow)`


Front starts with **(Born, Est. 1999, city)** beginner in round brackets. Following one-two sentences of description every front sentence ends with footnote links styled with **squared brackets** <span id="a1">[\[1\]](#f1)</span>, <span id="a2">[\[2\]](#f2)</span>, <span id="a3">[\[3\]](#f3)</span>.

The following code for footnote link

`<span id="a1">[\[1\]](#f1)</span>`

Will be rendered as

<span id="a1">[\[1\]](#f1)</span>


# Image, caption, and credits

This is image link code

`![](/encyclopedia/images/image-name.jpg)`

This is image caption code

`**Image caption**`

Will be rendered as

**Image caption**

This is image credits code

`*Photo: [Photographer name](photographer-name) / [Source name](edition-name)*`

It will be rendered as

*Photo: [Photographer name](photographer-name) / [Source name](edition-name)*

Every image must be described and styled with **bold font**. Credits line starts with **photographer's name** styled *italic* with an active link and after slash separator a source, or/and edition name. Links may also be pointed to **not existing pages** with syntax **photographer-name** or **edition-name**.

# Conspectus

Conspectus is for any structured data in table, the following code

`|Year|City|`
`|---|---|`
`|2014|Tokyo|`
`|2015|Moscow|`
`|2017|Paris|`

Will be rendered as

|Year|City|
|----|-----|
|2014|Tokyo|
|2015|Moscow|
|2017|Paris|

# See also

See also section connects your page with others pages in Indexmod Encyclopedia. Use following template combining list and link styling syntax. The code

`+ [See also title one](page-template-1)`

Will be rendered as

+ [See also title one](page-template-1)


# Footnotes

Code for footnote

`[[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)] (http://example.net/article)`

Will be rendered as

[[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)

Connect some text using short links <span id="a1">[\[1\]](#f1)</span>, <span id="a2">[\[2\]](#f2)</span>, <span id="a3">[\[3\]](#f3)</span> with links and source in **Footnote** edit. Kepp numbering in links organized: [[1]](#a1) <span id="f1"></span> [Article 1 (Author 1)](http://example.net/article)

![Снимок экрана 2018-02-27 в 8.19.05.png]({{site.baseurl}}/Снимок экрана 2018-02-27 в 8.19.05.png)

**This is screen of Prose.io editor during editing section below. Note the Save "disk" icon on rignt menu.**

# Prose.io editor

Every page may be edited in [Prose.io](www.prose.io) editor using link "Edit the "page name"" at top-left section of each page. To save  changes you may need have an account and be authorized as [GitHub](https://github.com/join) user.

`Updated Mar. 2018 (Andrei Dei)`
