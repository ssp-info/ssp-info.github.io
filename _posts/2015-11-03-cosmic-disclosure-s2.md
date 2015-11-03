---
layout: default
img: cosmic-disclosure-s2.jpg
category: cosmic_disclosure_s2
title: Космическое Раскрытие. Сезон 2.
description: |
---

<div>
  <h4>Интервью с Кори Гудом</h4>

  <ul>
    {% for intv in site.data.intv-corey-s2 %}

    <li>
      <a href="{{ intv.link }}" title="{{ intv.eng_title }}">
        {{ intv.title }}
      </a>
    </li>

    {% endfor %}
  </ul>

</div>
