<table>
  <thead>
    <tr>
    {% for header in site.data.syllabus.keys %}
      <td class="block"><b>{{header}}</b></td>
    {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.syllabus.content %}
    <tr>
    {% for column in row %}
      <td class="block">{{column}}</td>
    {% endfor %}
    </tr>
    {% endfor %}
  </tbody>
</table>