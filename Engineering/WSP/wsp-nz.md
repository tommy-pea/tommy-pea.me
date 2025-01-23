---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: tag
taxonomy: WSP NZ 
title: WSP in New Zealand
permalink: /engineering/wsp-nz/

sidebar:
  nav: engineering

---

The first two years of my career were spent at WSP NZ.

{% assign sorted_posts = site.WSP_UK %}
{% for post in sorted_posts %}
{% include archive-single.html %}
{% endfor %}