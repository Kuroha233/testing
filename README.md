# testing

{% for student in site.stu %}
<p>
  >><a><img src="{{ student.image }}"></a>@
  <a href="https://github.com/{{ student.user }}">
      {{ student.user }}
    </a> ({{ student.name }})
  <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>{{ student.content }}
 </p>
{% endfor %}

[author](https://github.com/Kuroha233)
