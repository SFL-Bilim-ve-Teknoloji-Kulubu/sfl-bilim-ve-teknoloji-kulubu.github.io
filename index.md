---
title: "Ana Sayfa"
layout: splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/anasayfa/1.jpg
  actions:
    - label: "Learn More"
      url: "/terms/"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
gallery:
  - url: /assets/anasayfa/1.jpg
    image_path: /assets/anasayfa/1.jpg

  - url: /assets/anasayfa/2.jpg
    image_path: /assets/anasayfa/2.jpg

  - url: /assets/anasayfa/3.jpg
    image_path: /assets/anasayfa/3.jpg

  - url: /assets/anasayfa/4.jpg
    image_path: /assets/anasayfa/4.jpg

  - url: /assets/anasayfa/5.jpg
    image_path: /assets/anasayfa/5.jpg


feature_row2:
  - image_path: /assets/img/logo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/img/logo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/img/logo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include gallery%}

<hr>
## Son Duyurular
{% for post in site.categories.Duyurular limit: 5 %}
  {% include archive-single.html %}
{% endfor %}
<hr>

