
### Our Collaborators


{% for col in site.data.collaborators %}
<hr>
<div id = "{{col.name}}" style="padding-top: 60px; margin-top: -60px;">
<p><strong>{{col.name}}</strong> - <em>{{col.position}}</em><br>
{% if col.startdate %} {{col.startdate}} - {% endif %}{{col.enddate}} <br>
Subsequent Position: {{col.current}} </p>
</div> {% endfor %}

<br>
