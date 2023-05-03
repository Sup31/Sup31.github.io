---
Academic Projects
====


* Personality Prediction Using Machine Learning, UCSC, Winter-Spring 2023
 * Pandora dataset


* Sign Language Recognition Using Convolutional Neural Networks, NMIMS, 2018-2019
 * Collected a database for Indian Sign Language and experimented with various architectures of CNNs using Tensorflow and Keras.



layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
---
