---
layout: default
---

<!-- <div class="grid-x">
  <div class="cell center">
    <span class="announcement">A new and improved website is coming soon - stay tuned.</span>
    <img src="/assets/img/hero.svg" />
  </div>
</div> -->

# Welcome to Rosslyn Farms
Founded in 1902 by the Chartiers Land Company, the Borough of Rosslyn Farms was developed by William Hayes Parrish, whose descendants still live here.  Rosslyn Farms is a small suburban borough conveniently located 5 miles west of Pittsburgh and 10 miles east of the Pittsburgh International Airport. It is a small community (0.6 square miles) consisting of 194 homes. At the heart of the Borough is the Rosslyn Farms Community Center, which provides meeting and recreational facilities for numerous civic events and youth activities.

<div class="grid-x">
  <div class="cell medium-4 large-12">
    <h2>Recent Last Word Editions</h2>
    <div class="grid-x">
      {% assign sorted_last_word_posts = site.lastwords | sort: 'date' | reverse %}
      {% for post in sorted_last_word_posts limit:3 %}
        <div class="cell large-4">
          <a href="/assets/pdf/lastwords/{{ post.pdf }}" target="_blank">
            {{ post.title }}
          </a>
        </div>
      {% endfor %}
    </div>
  </div>

  <div class="cell medium-4 large-12">
    <h2>Quick Links</h2>
    <div class="grid-x">
      <div class="cell large-4">
        Links
      </div>
      <div class="cell large-4">
        Links
      </div>
      <div class="cell large-4">
        Links
      </div>
    </div>
  </div>

  <div class="cell medium-4 large-12">
    <h2>News</h2>
    <div class="grid-x">
      <div class="cell large-4">
        News
      </div>
      <div class="cell large-4">
        News
      </div>
      <div class="cell large-4">
        News
      </div>
    </div>
  </div>
</div>
