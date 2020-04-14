---
title: Database & Data sharing
featured-img: openneuroscience
author: amchagas
layout: page
categories: [Topic]
---


Hard to believe, but there are actually open source projects for data sharing and analysis. They cover from fMRI to genetic/molecular data and go from &#8220;simply&#8221; turning paper data into images where the brain active regions are mapped, like the [Neurosynth project](http://neurosynth.org) to open databases where anyone can download a data set and analyse it the way they want, which is the case of the [INCF](http://www.incf.org/). In the end both sides win, the side that collected the data, since they have to be mentioned by the people who analysed the data.


Another information source on wikipedia: [Neuroscience databases](http://en.wikipedia.org/wiki/List_of_neuroscience_databases)



<section class="blog">
  <div class="container">
    <div class="post-list" itemscope="" itemtype="http://schema.org/Blog">

      {% for page in site.pages %}
        {% for category in page.categories %}
          {% if category == "Database" %}
            {% include card_page.html %}
          {% endif %}
        {% endfor %}
      {% endfor %}


    </div>
  </div>
</section>
