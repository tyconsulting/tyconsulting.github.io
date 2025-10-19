---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#4f7ccb"
  overlay_filter: "0.0"
  overlay_image: /assets/images/front-page-cloud.png
  #actions:
    #- label: "Download"
      #url: "https://github.com/mmistakes/minimal-mistakes/"
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
#excerpt: "We are passionated about Microsoft Cloud Technology. We are the cloud consultants you can truely trust."
intro:
  - excerpt: 'We are passionated about Microsoft Cloud Technology. We are the cloud consultants you can truely trust.'
feature_row:
  - image_path: assets/images/azpolicylens.png
    alt: "AzPolicyLens"
    title: "AzPolicyLens"
    excerpt: "A smarter way to bring visibility, consistency, and security to your Azure Cloud environment"
    url: "/azpolicylens/"
    btn_label: "AzPolicyLens"
    btn_class: "btn--primary"
  - image_path: assets/images/contact-us.png
    alt: "Contact Us"
    title: "Contact Us"
    excerpt: "We'd love to get in touch with you!"
    url: "/contact-us/"
    btn_label: "Contact Us"
    btn_class: "btn--primary"
  - image_path: /assets/images/about-us.png
    alt: "About Us"
    title: "About Us"
    excerpt: "Who we are and what we do?"
    url: "/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/coding2.png
    alt: "Downloads"
    title: "Downloads"
    excerpt: "Download free tools made by us"
    url: "/downloads/"
    btn_label: "Download"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}