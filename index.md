---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: blog
title: Home
nav_order: 1
permalink: '/'
---



<p>
<!-- {% comment %} -->
{% for page in sorted %}
    {{ page.title}} | {{ page.last_modified_at | date: '%s' }}
{% endfor %}
<!-- {% endcomment %} -->
</p>