| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.datavis | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}