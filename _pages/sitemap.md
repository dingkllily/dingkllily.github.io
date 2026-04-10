---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of the main pages and collections currently published on this site. For crawlers and indexing tools, there is also an [XML version]({{ base_path }}/sitemap.xml).

<h2>Pages</h2>
{% for post in site.pages %}
  {% if post.title and post.sitemap != false and post.permalink != '/404.html' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Projects</h2>
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
