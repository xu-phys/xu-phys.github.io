---
title: "Bin Xu's website - Talks"
layout: textlay
excerpt: "Talks"
sitemap: false
permalink: /talks
---

# Inivited Talks

{% for talk in site.data.talks_inv %}

  {{ talk.title }} <br />
  <b>{{ talk.conf }} </b><br />
  {{ talk.place }} <br />
  {{ talk.date }} <br />

{% endfor %}

# Contributed Talks

{% for talk in site.data.talks_contr %}

  {{ talk.title }} <br />
  <b>{{ talk.conf }} </b><br />
  {{ talk.place }} <br />
  {{ talk.date }} <br />

{% endfor %}

# Invited Seminars

{% for talk in site.data.talks_seminar %}

  {{ talk.title }} <br />
  <b>{{ talk.conf }} </b><br />
  {{ talk.place }} <br />
  {{ talk.date }} <br />

{% endfor %}
