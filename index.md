---
layout: default
---

# Welcome to The Farms
Founded in 1902 by the Chartiers Land Company, the Borough of Rosslyn Farms was developed by William Hayes Parrish, whose descendants still live here.  Rosslyn Farms is a small suburban borough conveniently located 5 miles west of Pittsburgh and 10 miles east of the Pittsburgh International Airport. It is a small community (0.6 square miles) consisting of 194 homes. At the heart of the Borough is the Rosslyn Farms Community Center, which provides meeting and recreational facilities for numerous civic events and youth activities.

# Last Word

{% assign sorted_last_word_posts = site.lastwords | sort: 'date' | reverse %}
{% for post in sorted_last_word_posts limit:3 %}
  <a href="/assets/pdf/lastwords/{{ post.pdf }}" target="_blank">{{ post.title }}</a>
{% endfor %}
