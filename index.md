---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
classes: landing
title: Thomas Prince
tagline: An engineer and musician
author_profile: true
header: 
  overlay_filter: 0.3
  overlay_image: assets/images/splash_header.png

intro: 
  - excerpt: '

  I am an excellent data analyst, visualiser, communicator, and problem solver.\

  I can solve and communicate complex problems using Python, R, and MATLAB.

  '

feature_row:
  - image_path: assets/images/iceland.jpeg
    title: About me
    excerpt: A brief summary of highlights and achievements.
    url: /about/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/lorenz.jpeg
    title: Engineering
    excerpt: I studied engineering science and have experience in engineering consulting.
    url: /engineering/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/gypsy_jazz.jpeg
    title: Music
    excerpt: I play violin and studied classical performance.
    url: /music/
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

I studied at the University of Auckland. I have a Bachelor of Engineering (Honours) with First Class Honours specialising in Engineering Science and a Bachelor of Music majoring in Classical Performance on violin.

Since graduating, I have worked at WSP for three years between Wellington, Auckland, Leeds, and London in the transport sector. My most recent role was Transport Net Zero Consultant at WSP UK in London.

{% include feature_row id="feature_row" %}