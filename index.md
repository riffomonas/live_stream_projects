---
layout: page
title: Live Streaming Data Analysis
---

Something clever...

<ul class="post-preview">
  {% for post in site.live_streams %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
			{% if post.blurb != nil %}
			<p>{{ post.blurb }}</p>
			{% else %}
		      {{ post.excerpt }}
			{% endif %}
    </li>
  {% endfor %}
</ul>
