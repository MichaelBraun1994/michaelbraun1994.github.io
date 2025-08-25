---
title: /docs
layout: home
permalink: /docs
---

# Docs

A curated list of books and articles that offered me valuable insights.

# Computer Science

{% for book in site.data.books.computer_science_books %}
## {{ book.title }}
*(By {{ book.author }}, {{ book.published }}, ISBN: {{ book.isbn }})*
<p>{{ book.description }}</p>
{% endfor %}
