# testing

{% for student in site.stu %}
  <p>>>![student_image]({{ student.image }} "{{ student.user }}")@
  <a href="https://github.com/{{ student.user }}">
      {{ student.user }}
    </a> ({{ student.name }})</p>
  <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;>>{{ student.content | markdownify }}</p>
  
  
{% endfor %}

[author](https://github.com/Kuroha233)
