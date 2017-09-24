---
title: "Bin Xu's website - Talks"
layout: textlay
excerpt: "Talks"
sitemap: false
permalink: /talks
---

## Full List

* 2017

{% for publi in site.data.publist_2017 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

* 2016

{% for publi in site.data.publist_2016 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

* 2015

{% for publi in site.data.publist_2015 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

* 2014

{% for publi in site.data.publist_2014 %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

* 2006 - 2013

{% for publi in site.data.publist_older %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

<!-- <figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/DSC_0696.jpg" width="95%">
</figure> -->
