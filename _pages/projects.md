---
layout: archive
title: "Arizona State University Projects"
permalink: /projects/
author_profile: true
feature_row2:
  - image_path: /assets/images/ML.jpg
    alt: "placeholder image 2"
    title: "Statistical Machine Learning"
    excerpt: 'MNIST Classification and K-means Clustering'
    url: "https://github.com/John-jg-park/Statistical-Machine-Learning"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/Bigdata.jpg
    alt: "placeholder image 2"
    title: "Data Processing at Scale"
    excerpt: 'NoSQL(MongoDB) and Spark SQL'
    url: "https://github.com/John-jg-park/Data-Processing-at-Scale"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/datamining.jpg
    alt: "placeholder image 2"
    title: "Data Mining"
    excerpt: 'Machine Model Training and Cluster Validation'
    url: "https://github.com/John-jg-park/Data-Mining"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/computervision.jpg
    alt: "placeholder image 2"
    title: "Introduction to Deep Learning in Visual Computing"
    excerpt: 'Deep Learning for Computer Vision'
    url: "https://github.com/John-jg-park/Introduction-to-Deep-Learning-in-Visual-Computing"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/mobile.jpg
    alt: "placeholder image 2"
    title: "Mobile Computing"
    excerpt: 'Mobile application development using Android Studio and CNN model Train/Test'
    url: "https://github.com/John-jg-park/Mobile-Computing"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row4" type="left" %}
{% include feature_row id="feature_row5" type="left" %}
{% include feature_row id="feature_row6" type="left" %}
