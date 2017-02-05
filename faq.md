---
layout: page
title: frequently asked questions
permalink: /frequently-asked-questions/
---
{% capture faq %}{% include editables/faq-text.md %}{% endcapture %}
{{ faq | markdownify }}
