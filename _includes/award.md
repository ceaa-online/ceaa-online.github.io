## {{ include.award.name }} {{ include.award.title }}

{{ include.award.description }}

### Recipients
{:.color-navy.italic}

{% for recipient in include.award.recipients %}
{% include recipient.html %}
{% endfor %}
