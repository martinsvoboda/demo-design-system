# Design System Template

Design System Template is a boilerplate for creating and documenting your principles, style guides and patterns for your organization's design system. It provides just enough IA and hooks to get you going. As a bonus, I've provided links to helpful resources and inspiration to help you as you create your own custom design system. It is based on Brad Frost [Style Guide Guide](https://github.com/bradfrost/style-guide-guide/). The original code was cleaned and reworked, which leads to more straightforward maintenance of patterns and pages. Also we speed up site generation.

[See the demo here](https://martinsvoboda.github.io/mpsv-design-system/)

## How it works
Style Guide Guide is built using [Jekyll](https://jekyllrb.com/), a static site generator which works quite well for managing the content of a style guide.


## Installation

1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
2. Download or clone the files from the [repository on Github](https://github.com/martinsvoboda/mpsv-design-system). If you starting with GIT see [simple guide](http://rogerdudler.github.io/git-guide/), you can use [GitHub desktop klient](https://desktop.github.com/)
3. In the command line, navigate to the root of the project and run the `jekyll serve` command. This will build the static site and watch for changes.
3. Visit `http://127.0.0.1:4000/` in your browser to see the style guide.


## Build your design system

From here, obviously the point is to customize the style guide for your needs and populate it with your content and components. Content is formatted in Markdown syntax. See [how to use it](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Add page

If you want create new page::

1. Create new file `my-first-page.md` with content

```
---
layout: page
title: My First Page
description: The description of page.
---

## Heading

Lorem ipsum
```

2. Go to `http://127.0.0.1:4000/my-first-page.html` and see your first page.


### Add component

### How to edit navigation

Navigaci lze upravovat v _includes/navigation.html. Pro vložení položky využijte::

    {% include navigation-item.html path='/index.html' label='Úvod' %}

Pro vložení sub navigace uveďte parametr skupiny. Podpoložky se vloží automaticky na základě jména skupiny::

    {% include navigation-item.html group='page-templates' label='Šablony stránek' %}


## Feedback and Questions
If you have questions or issues with Style Guide Guide, please feel free to [open an issue](https://martinsvoboda.github.io/mpsv-design-system/issues).
