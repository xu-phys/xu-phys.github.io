---
title: "Bin Xu's website - Teaching"
layout: textlay
excerpt: "Bin Xu's website -- Teaching"
sitemap: false
permalink: /teaching/
---

# Lecturer

{% for teach in site.data.lecturer %}

  <b>{{ teach.title }}</b> <br />
  * {{ teach.univ }} <br />
  * {{ teach.year }} <br />
  * {{ teach.details }} <br />

{% endfor %}

# Guest Lecturer

{% for teach in site.data.lecturer %}

  <b>{{ teach.title }}</b> <br />
  * {{ teach.univ }} <br />
  * {{ teach.year }} <br />
  * {{ teach.details }} <br />

{% endfor %}

# Teaching assistant

{% for teach in site.data.ta %}

  <b>{{ teach.title }}</b> <br />
  * {{ teach.univ }} <br />
  * {{ teach.year }} <br />
  * {{ teach.details }} <br />

{% endfor %}
