---
layout: default
img: cosmic-disclosure-s4.jpg
category: cosmic_disclosure_s4
title: Космическое Раскрытие. Сезон 4.
description: |
---

<div>
  <h4>Интервью с Кори Гудом</h4>

  <ul>
    {% for intv in site.data.intv-corey-s4 %}

    <li>
      <a href="{{ intv.link }}" title="{{ intv.eng_title }}">
        {{ intv.title }}
      </a>
    </li>

    {% endfor %}
  </ul>

</div>
