---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

This page provides a structured overview of all content available on this website. For search engine crawlers, an [XML version]({{ base_path }}/sitemap.xml) is also available.

<div class="archive__subtitle">Pages & Posts</div>

{% for page in site.pages %}
  {% if page.title %}
    {% include archive-single.html post=page %}
  {% endif %}
{% endfor %}

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

<hr>

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" or collection.label == "data" %}
    
    {% capture label %}{{ collection.label }}{% endcapture %}
    
    <h2>
      {% if label == "publications" %}
        Selected Publications
      {% elsif label == "talks" %}
        Talks & Presentations
      {% elsif label == "teaching" %}
        Teaching Experience
      {% elsif label == "portfolio" %}
        Projects & Portfolio
      {% else %}
        {{ label | capitalize }}
      {% endif %}
    </h2>

    {% for post in collection.docs %}
      {% include archive-single.html %}
    {% endfor %}
    
  {% endunless %}
{% endfor %}
