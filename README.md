# testing

{% for student in site.stu %}
<p>
>><a><img src="{{ student.image }}"></a><a href="https://github.com/{{ student.user }}">@{{ student.user }}</a> ({{ student.name }}){{ student.content | markdownify }}
</p>
<br>
{% endfor %}

Author: [Kuroha233](https://github.com/Kuroha233)
