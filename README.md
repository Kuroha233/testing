# testing

{% for student in site.stu %}
<p>
*<a><img src="{{ student.image }}"></a>@<a href="https://github.com/{{ student.user }}">{{ student.user }}</a> ({{ student.name }})
  *{{ student.content }}
</p>
<br>
{% endfor %}

[Kuroha233](https://github.com/Kuroha233)
