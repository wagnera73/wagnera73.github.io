| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.versioncontrol | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}