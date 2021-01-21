---
layout: splash # splash home
entries_layout: grid #grid #list
author_profile: false
classes: wide

permalink: /
title: "JWA Classic"
excerpt: "Just the cars we love"

header:
  #overlay_color: "#333"
  overlay_image: /assets/images/banner-talbot-lago-t150c.jpg
  overlay_filter: 0.4 # same as adding an opacity of 0.5 to a black background
  actions:
     - label: "La Collection"
       url: "/la-collection/"
     - label: "News & Blogs"
       url: "/news-blogs/"


feature_row_1:
 - image_path: /assets/images/20170520_170024.jpg
   title : "Welcome text"
   excerpt: "Coucou Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
   url: "/la-collection/"
   btn_label: "La Collection"
   btn_class: "btn--inverse"

feature_row_2:
 - image_path: /assets/images/posts/image1.jpeg
   title : "Extrait du dernier post"
   excerpt: "On pourrait mettre un extrait du dernier post, mais ça devra se faire à la main et ça deviendra vite lourd...<br>
   sinon, on peut faire une mise en page comme [ici](/news-blog-test2/)"
   url: '/latest-news/category3/RS26six-postessai6/'
   btn_label: "More"
   btn_class: "btn--inverse"

---
# Welcome
{% include feature_row id="feature_row_1" type="right" %}

# Latest post from our blog
{% include feature_row id="feature_row_2" type="left" %}
