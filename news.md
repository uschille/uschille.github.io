---
layout: page
group: navigation
title: News
headline: News from Ulf Schiller's Research Group
tagline:
---

<div class="home">

  <ul class="posts">
    {% for post in site.posts %}
      <li><span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span> <a class="post-link" href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
