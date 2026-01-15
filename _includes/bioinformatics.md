| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.bioinformatics | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}