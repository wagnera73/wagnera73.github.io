| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.machinelearning | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}