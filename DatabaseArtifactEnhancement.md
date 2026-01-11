---

layout: page
title: (WIP) Database Artifact Enhancement
---

{% for file in site.static_files %}
{% if file.path contains '/DatabaseArtifactEnhancement/' %}
- [{{ file.name }}]({{ file.path }})
{% endif %}
{% endfor %}
