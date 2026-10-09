---
layout: page
title: photos
permalink: /photos/
---

Mostly field photos

<div class="gallery">
{% for photo in site.data.photos %}
  <figure>
    <img src="{{ photo.file | relative_url }}"
         alt="{{ photo.alt }}"
         loading="lazy"
         decoding="async" />
    {% if photo.caption %}<figcaption>{{ photo.caption }}</figcaption>{% endif %}
  </figure>
{% endfor %}
</div>
