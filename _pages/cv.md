---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: Academic_CV_12102025.pdf
---
{% if page.cv_pdf %}
<p>See my CV <a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url }}" target="_blank" rel="noopener noreferrer">here</a>.</p>
{% else %}
<p>The PDF version of my CV will be available soon.</p>
{% endif %}
