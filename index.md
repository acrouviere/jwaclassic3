---
layout: splash # archive
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
   excerpt: "Voir comment automatiser un extrait du dernier post des blogs, on pourra le faire à la main dans un 1er temps"
   url: '/delage-d8-120-chapron/'
   btn_label: "More"
   btn_class: "btn--inverse"

feature_row_3:
 - image_path: /assets/images/thb-delahaye-type-235-235m-breitling.jpg
   title : "Delahaye 235 Breitling"
   excerpt: "Delahaye 235 Breitling - 19XX"
   url: "/delahaye-235-breitling/"
   btn_label: "More"
   btn_class: "btn--inverse"

feature_row_4:
- image_path: /assets/images/thb-aston-martin-international-cadbury.jpg
  title : "Aston Martin"
  excerpt: "Aston Martin International - 19XX"
  url: "/aston-martin-international-cadbury/"
  btn_label: "More"
  btn_class: "btn--inverse"

feature_row_5:
- image_path: /assets/images/thb-delahaye-type-135-135M-chapron.jpg
  title : "Delahaye 135-M Chapron"
  excerpt: "Delahaye 135-M Chapron - 19XX"
  url: '/delahaye-135-135M-chapron/'
  btn_label: "More"
  btn_class: "btn--inverse"

feature_row_6:
- image_path: /assets/images/thb-alfa-romeo-giulietta-sprint-speciale-1300-ss.jpg
  title : "Alfa Romeo Giulietta Sprint Speciale"
  excerpt: "Alfa Romeo 1300 Sprint Speciale - 1962"
  url: "/alfa-romeo-giulietta-sprint-speciale-1300-ss/"
  btn_label: "More"
  btn_class: "btn--inverse"




#{% include feature_row id="feature_row1" type="right" %}

---



{% include feature_row id="feature_row_1" type="right" %}


{% include feature_row id="feature_row_2"  type="left" %}
