
### Our Collaborators


{% for collaborator in site.data.collaborator %}
<hr>
<div id = "{{collaborator.name}}" style="padding-top: 60px; margin-top: -60px;">
<p><strong>{{collaborator.name}}</strong> - <em>{{collaborator.position}}</em><br>
{% if collaborator.startdate %} {{collaborator.startdate}} - {% endif %}{{collaborator.enddate}} <br>
Subsequent Position: {{collaborator.current}} </p>
</div> {% endfor %}

<br>
