---
layout: default
img: cosmic-disclosure-s1.jpg
category: cosmic_disclosure_s1
title: Космическое Раскрытие. Сезон 1.
description: |
---

<div>
  <h4>Интервью с Кори Гудом</h4>

  <ul>
    {% for intv in site.data.intv-corey-s1 %}

    <li>
      <a href="{{ intv.link }}" title="{{ intv.eng_title }}">
        {{ intv.title }}
      </a>
    </li>

    {% endfor %}
  </ul>

</div>
