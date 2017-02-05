---
layout: page
title: faq
permalink: /frequently-asked-questions/
---
{% capture faq %}{% include editables/faq-text.md %}{% endcapture %}
{{ faq | markdownify }}
