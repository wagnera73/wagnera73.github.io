| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.webdev | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}