---
layout: page
permalink: /tags/
title: Explore by tag
---

<section class="taxonomies">
  {% assign tags = site.tags | sort %}
  {% if tags.size > 0 %}
    <ul class="taxonomy-list">
      {% for tag in tags %}
        <li>
          <h2 id="{{ tag[0] }}">{{ tag[0] | replace: '_', ' ' }}</h2>
          <ul>
            {% for post in tag[1] %}
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
    <p>No tags yet. Check back soon.</p>
  {% endif %}
</section>
