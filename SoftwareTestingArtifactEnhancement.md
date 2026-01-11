---

layout: page
title: (WIP) Software Testing Artifact Enhancement
---

{% for file in site.static_files %}
{% if file.path contains '/Software Testing Artifact Enhancement/' %}
- [{{ file.name }}]({{ file.path }})
{% endif %}
{% endfor %}
