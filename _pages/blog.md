---
title: Blog
permalink: /blog
---
### Posts:
{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% include documents-collection.html entries=site.posts type=entries_layout %}
</div>
