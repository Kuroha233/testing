# testing

{% for student in site.stu %}
  <p>>>![student_image]({{ student.image }} "{{ student.user }}")@[{{ student.user }}](https://github.com/{{ student.user }}) ({{ student.name }})</p>
  <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>{{ student.content | markdownify }}</p>
{% endfor %}
