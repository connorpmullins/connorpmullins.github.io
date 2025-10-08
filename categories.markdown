---
layout: page
permalink: /categories/
title: Explore by category
---

<section class="taxonomies">
  {% assign categories = site.categories | sort %}
  {% if categories.size > 0 %}
    <ul class="taxonomy-list">
      {% for category in categories %}
        <li>
          <h2>{{ category[0] | replace: '_', ' ' }}</h2>
          <ul>
            {% for post in category[1] %}
              <li>
                <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
                <span class="taxonomy-date">{{ post.date | date: "%b %-d, %Y" }}</span>
              </li>
            {% endfor %}
          </ul>
        </li>
      {% endfor %}
    </ul>
  {% else %}
    <p>No categories yet. Check back soon.</p>
  {% endif %}
</section>
