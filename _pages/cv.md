---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: example_pdf.pdf
description: Download a copy of my CV.
---

{% if page.cv_pdf %}
[Download my CV (PDF)]({{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}){: .btn .btn--primary target="_blank" rel="noopener noreferrer"}
{% else %}
<p>The PDF version of my CV will be available soon.</p>
{% endif %}
