# {{ include.award-category.title }}

{{ include.award-category.description }}

{% for award in include.award-category.list %}
### {{ award.name }}
{:.color-navy.italic}

{{ award.description}}
{% endfor %}
