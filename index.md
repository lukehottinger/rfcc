---
layout: index
announcement: Sign Up For Your 2020 RFCC Membership <strong><a href="/membership">Here</a></strong> Today!
hero: index-hero.jpg
hero-credits: WikiMedia Commons
---

<!-- <div class="grid-x">
  <div class="cell center">
    <span class="announcement">A new and improved website is coming soon - stay tuned.</span>
    <img src="/assets/img/hero.svg" />
  </div>
</div> -->

# Welcome to Rosslyn Farms

Welcome. Thank you for visiting the Rosslyn Farms Community Club (the Club) website. For almost 120 years, the Club has enriched the community by developing social, educational, and civic interests. Our various committees work hard throughout the year to bring beauty and laughter to Rosslyn Farms for those of all ages.

Founded in 1902 by the Chartiers Land Company, the Borough of Rosslyn Farms was developed by William Hayes Parrish, whose descendants still live here.  Rosslyn Farms is a small suburban borough conveniently located 5 miles west of Pittsburgh and 10 miles east of the Pittsburgh International Airport. It is a small community (0.6 square miles) consisting of 194 homes. At the heart of the Borough is the Rosslyn Farms Community Center, which provides meeting and recreational facilities for numerous civic events and youth activities.

<h2>Recent Last Word Editions</h2>
<div class="grid-x">
  {% assign sorted_last_word_posts = site.lastwords | sort: 'date' | reverse %}
  {% for post in sorted_last_word_posts limit:2 %}
    <div class="cell large-4">
      <a href="/assets/pdf/lastwords/{{ post.pdf }}" target="_blank">
        <div class="card">
          <!-- <img src="https://via.placeholder.com/256.png" /> -->
          <img src="/assets/img/lastwords/{{ post.thumb }}" />
          <span class="title">{{ post.title }}</span>
        </div>
      </a>
    </div>
  {% endfor %}
</div>

<!-- <div class="grid-x">
  <div class="cell medium-4 large-12">

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
</div> -->
