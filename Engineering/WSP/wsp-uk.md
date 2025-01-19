---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: tag
taxonomy: WSP UK
title: WSP in the UK
permalink: /engineering/career/wsp-uk/
breadcrumbs: False

sidebar:
  nav: engineering

---

I have worked at WSP UK since March 2024.
My role is Transport Net Zero Consultant.


{% for post in site.categories.WSP_UK %}
{% include archive-single.html %}
{% endfor %}