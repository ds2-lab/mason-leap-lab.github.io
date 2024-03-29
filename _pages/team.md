---
title: "LeapLab - Team"
layout: gridlay
excerpt: "LeapLab: Team members"
sitemap: false
permalink: /team/
---

# Team Members

 **We are looking for new PhD students, master students, and
undergrad students to join the team!**


Jump to [faculty](#faculty), [phd students](#phd-students), [master students](#master-students), [undergrad students](#undergrad-students), [alumni](#alumni), and [former students](#former-undergrad-and-master-students).

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{member.email}}</i>
  <ul style="overflow: hidden">

  {% if member.number_ric == 1 %}
  <li> {{ member.ri1 }} </li>
  {% endif %}

  {% if member.number_ric == 2 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  {% endif %}

  {% if member.number_ric == 3 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  {% endif %}

  {% if member.number_ric == 4 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  {% endif %}

  {% if member.number_ric == 5 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  <li> {{ member.ri5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.phd_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_ric == 1 %}
  <li> {{ member.ri1 }} </li>
  {% endif %}

  {% if member.number_ric == 2 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  {% endif %}

  {% if member.number_ric == 3 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  {% endif %}

  {% if member.number_ric == 4 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  {% endif %}

  {% if member.number_ric == 5 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  <li> {{ member.ri5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Master's Students
{% assign number_printed = 0 %}
{% for member in site.data.master_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_ric == 1 %}
  <li> {{ member.ri1 }} </li>
  {% endif %}

  {% if member.number_ric == 2 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  {% endif %}

  {% if member.number_ric == 3 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  {% endif %}

  {% if member.number_ric == 4 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  {% endif %}

  {% if member.number_ric == 5 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  <li> {{ member.ri5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



## Undergrad Students
{% assign number_printed = 0 %}
{% for member in site.data.undergrad_students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_ric == 1 %}
  <li> {{ member.ri1 }} </li>
  {% endif %}

  {% if member.number_ric == 2 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  {% endif %}

  {% if member.number_ric == 3 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  {% endif %}

  {% if member.number_ric == 4 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  {% endif %}

  {% if member.number_ric == 5 %}
  <li> {{ member.ri1 }} </li>
  <li> {{ member.ri2 }} </li>
  <li> {{ member.ri3 }} </li>
  <li> {{ member.ri4 }} </li>
  <li> {{ member.ri5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Former Undergrad and Master Students
<div class="row">

<div class="col-sm-6 clearfix">
<h4>Undergrad Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

</div>

