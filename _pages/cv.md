---
title: "Xu group @ Soochow University - CV"
layout: gridlay
excerpt: "Xu group @ Soochow University - CV"
sitemap: false
permalink: /cv/
---

# Curriculum vitae

<!--  **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors). -->

<!-- ## Staff -->
{% assign number_printed = 0 %}
{% for member in site.data.cv %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
<br>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
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

## Editorial Activities

(2013-2014) <b>Guest editor</b> Advances in Multiscale Modeling and Computational Mechanics, Hindawi

(2009-now) <b>Journal Referee/Reviewer</b> Nature Communications, Advanced Materials, Physical Review Letters, Physical Review Applied, ACS Chemistry of Materials, Advanced Electronic Materials, Advanced Materials Interfaces, Small, Nanoscale, Physical Review B, Physical Review Materials, Journal of Physics: Condensed Matter, The Journal of Physical Chemistry, Scientific Reports, Journal of Applied Physics, Journal of the American Ceramic Society, Physica Status Solidi B: Basic Solid State Physics, New Journal of Physics, Computational Materials Science, Journal of Alloys and Compounds, Journal of Physics D: Applied Physics, Physica B, Chinese Physics B, High Pressure Research

<!--


## Master and Bachelor Students 
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
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
<table align="center" style="width:100%">
<tr><th>Visitors</th>
    <th>Master Students</th> 
    <th>Bachelor Students</th>
  </tr>
  <tr>
    <td>Nikolaos Iliopoulos, Spring 2016</td>
    <td>Tjerk Benschop, Summer 2017</td>
    <td>Vishnu Saj, Spring 2017</td>
  </tr>
  <tr>
    <td>Vitaly Fedoseev, all of 2016</td>
    <td>Oliver Ostojic, Spring 2016</td>
    <td>Joey Braspenning, Spring 2017</td>
  </tr>
  <tr>
    <td></td>
    <td>Farshaad Hoeseni, Fall 2015</td>
    <td>Margot Leemker, Spring 2017</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Sietske Lensen, Spring 2017</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Alexander Vanstone, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Tjerk Benschop, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Arjo Andringa, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Daniëlle van Klink, Spring 2016</td>
  </tr>
</table>

## Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration.

## Lab Guests

[Amir Safavi-Naeini](http://stanford.edu/~safavi/) (Stanford), summer 2015

[Mark H Fischer](https://people.phys.ethz.ch/~mfischer/) (Weizmann Institute of Science), fall 2015

[Alexander Ako Khajetoorians](http://www.ru.nl/spm) (Radboud University), fall 2015

[Mohammad Hamidian](http://www.mhamidian.com) (Harvard->UC Davis), spring 2016

[Ivan Bozovic](https://www.bnl.gov/cmpmsd/mbe/default.asp) (BNL / Yale), spring 2016

[Freek Massee](http://www.fmassee.nl) (Paris), spring 2016

[Felix Baumberger](http://dqmp.unige.ch/baumberger/) (Geneva), spring 2016

[Jasper van Wezel](http://www.jvanwezel.com/) (UvA), summer 2016 -->
