---
layout: default
title: Welcome to EBiafra
---

# Welcome to EBiafra

## A Historical Non-Fiction Resource

EBiafra is dedicated to documenting and exploring the complex history of Biafra, one of the most significant historical events in modern African history.

### About This Site

This website serves as a comprehensive resource for historical research, documentation, and education about the Biafran conflict and its historical context.

### Key Topics

- **Historical Background** - The foundations and context leading to Biafran independence
- **The Biafran War** - Detailed accounts of the 1967-1970 conflict
- **Cultural Heritage** - Exploration of Biafran culture, people, and traditions
- **Legacy and Impact** - How these events shaped modern Nigeria and Africa

---

## Latest Articles

{% for post in site.posts limit:5 %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[Read All Articles](/blog/)