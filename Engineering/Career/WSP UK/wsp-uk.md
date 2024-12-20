---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: tag
taxonomy: WSP UK
title: WSP in the UK
permalink: /engineering/career/wsp-uk/

sidebar:
  nav: engineering

---

I have worked at WSP UK since March 2024.
The posts below detail my work experience and achievements.

{% for post in site.categories.WSP_UK %}

{% include archive-single.html %}

{% endfor %}