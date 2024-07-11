{% for member in site.data.styret %}
  
{{ member.name }} ({{ member.position }})

{% if member.phone %}
   - tlf: {{ member.phone }}
{% endif %}

{% if member.mail %}
   - e-mail: {{ member.mail }}
{% endif %}

{% endfor %}
