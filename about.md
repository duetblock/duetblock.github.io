---
layout: home
menu: about
title: About duetBlock.
title_img: /assets/img/logo_big.png
title_css: height:100px;
permalink: /about/
history:
  - name: now
    content: developing...
  - name: Nov 23, 2022
    content: Heavy Bowl (Google Play Store & Apple App Store) launched.
  - name: Aug 16, 2017
    content: neoDefense launched.
  - name: Jun 8, 2015
    content: duetBlock launched.
---

The duetBlock is a game name and a company founded by one-man indie game developer Son Gil

### History

<ul>
{% for item in page.history %}
  <li>
    {{ item.name }} _____ {{ item.content }}
  </li>
{% endfor %}
</ul>
