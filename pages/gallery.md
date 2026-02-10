---
layout: page
title: 图库
permalink: /gallery/
gallery_path: "assets/img/pexels"
excluded: true
position: 3
tags: [Page]
---

{% assign gallery_settings = site.data.site-content.gallery %}

{{ gallery_settings.subtitle }}

{% include gallery.html gallery_path=page.gallery_path %}
