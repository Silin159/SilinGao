---
layout: page
title: TA Work
permalink: /teaching/
---
<table>

  <thead>
    <tr>
      <th>Semester</th>
      <th>Course Code</th>
      <th>Name</th>
      <th>Professor</th>
      <!-- <th>Description</th> -->
    </tr>
  </thead>

  {% for course in site.data.teaching %}

  <tfoot>
    <tr>
      <td>{{ course.date }}</td>
      <td>{{ course.code }}</td>
      <td>{{ course.name }}</td>
      <td>{{ course.prof }}</td>
      <!-- <td>{{ course.desc }}</td> -->
    </tr>
  </tfoot>

  {% endfor %}


</table>