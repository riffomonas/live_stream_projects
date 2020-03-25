---
layout: page
title: Live Streaming Data Analysis
---

There are numerous resources out there for learning how to program. Have a
question about generating a line plot in Your Favorite Language? google it.
There are fewer resources out there on how to do a complete project from an
empty directory to a finished project. I made a very [lengthy series of
tutorials](http://www.riffomonas.org/reproducible_research/) on using
reproducible research practices to analyze 16S rRNA gene sequence data
covering everything from setting up the directory structure through generating
a manuscript that you can submit to your favorite journal. Those are tutorials,
which are meant to teach people how to do things. It was a bit contrived
because the data had already been published and I wasn't showing my thought
process as the project developed.

In these live streams the goal is to show and discuss the evolution of various
projects over the arc of an analysis. The first series I created was in the
summer of 2018 and was recorded before posting. To try to increase the social
dimension of these analyses, I will experiment with streaming the analysis
using google. Please like and subscribe the [Riffomonas YouTube](https://www.youtube.com/channel/UCGuktEl5InrcxPfCjmPWxsA/) channel so you
can be sure to learn of any updates. Although my goal is to eventually do a
microbiome-focused series of streams, the world is a bit too serious right now.
For now, let's have fun with a few quirky datasets.


<ul class="post-preview">

	{% assign sorted = (site.live_streams | sort: 'date') | reverse %}

  {% for post in sorted %}
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
