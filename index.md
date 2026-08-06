---
title: Data Intelligence Lab
layout: home
group: home
---

## About Us

We develop intelligent methods for learning and reasoning with complex real-world data, with a particular focus on **graph machine learning and its applications**.

Our research spans **Graph Representation Learning**, **Graph + LLM**, **Graph Applications**, **Trustworthy AI**, and **Industrial AI**.

---

## Recent News

<ul>
{% for post in site.posts limit: 5 %}
  <li>
    <b>{{ post.date | date: "%b %Y" }}</b> —
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<a href="/news/">More News →</a>
