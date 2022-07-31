---
title: Welcome to NDCP
menutitle: Home
layout: default
---

<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec porttitor arcu. Nulla at hendrerit sapien, id pulvinar ipsum. Phasellus et turpis eu ex tincidunt malesuada ut nec ligula. Quisque nibh enim, tincidunt sit amet lacinia quis, bibendum ut mi. Nulla consectetur tortor non lobortis interdum. Sed vel nisi ac mauris congue fringilla. In sollicitudin tincidunt sagittis.
</p>

## Announcements

<ul>
  {% for post in site.posts limit:3 %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
