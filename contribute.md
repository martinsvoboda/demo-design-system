---
layout: page
title: Contributing to the design system
description: This page explains the process (or processes) by which the design system gets updated
---

## People
Describe who's involved in changes to the system. Describe who's expected to do the work and who approves changes.

## Process
Describe specifically the process or processes by which the system gets [updated](http://atomicdesign.bradfrost.com/chapter-5/#making-changes-to-patterns). What happens when existing component need modified? What if an entire new component needs created? What happens if a component is deprecated? See [Canonical's fantastic decision tree](http://design.canonical.com/2016/07/getting-vanilla-ready-for-v1-the-roadmap/) for contributing changes to their design system.

Since a design system is made up of component code, guidelines, documentation, design tools, and resources, keep in mind you'll likely need to define several processes to contribute each of these ingredients.

## Support
Cross-linking to the <a href="{{ "/support.html" | prepend: site.baseurl }}">support page</a> is a good idea here.



## Instalace


## Práce s navigací

Navigaci lze upravovat v _includes/navigation.html. Pro vložení položky využijte::

    {% include navigation-item.html path='/index.html' label='Úvod' %}

Pro vložení sub navigace uveďte parametr skupiny. Podpoložky se vloží automaticky na základě jména skupiny::

    {% include navigation-item.html group='page-templates' label='Šablony stránek' %}

## Přidání stránky

## Přidání komponenty

## Utility

Pro zobrazení náhledu kódu komponenty na stránce můžete použít::

    {% include pattern_live.html path='_examples/buttons2/button2.html' %}

    {% include pattern_code.html path='_examples/buttons2/button2.html' %}