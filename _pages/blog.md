---
title: Blog posts
subtitle: blog posts
permalink: /blog/
layout: default
type: page
---

<div class="posts-list">
  {% for post in site.posts %}
  <article class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
	  <h2 class="post-title">{{ post.title }}</h2>

	  {% if post.subtitle %}
	  <h3 class="post-subtitle">
	    {{ post.subtitle }}
	  </h3>
	  {% endif %}
    </a>

    <p class="post-meta">
      Posted on {{ post.date | date: "%B %-d, %Y" }}
    </p>

    <div class="post-entry">
      {{ post.content | strip_html | xml_escape | truncatewords: 50 }}
	  <a href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</a>
    </div>

   </article>
  {% endfor %}
</div>

