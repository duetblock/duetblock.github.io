---
layout: home
menu: duetBlock
title: duetBlock
permalink: /duetBlock/
screens:
  - title: Playing screenshot
    imgurl: /assets/img/duetBlock1.png
  - title: Playing screenshot
    imgurl: /assets/img/duetBlock2.png
  - title: Playing screenshot
    imgurl: /assets/img/duetBlock3.png
  - title: Bomb combination
    imgurl: /assets/img/duetBlock4.png
---

<div class="">

  <div style="text-align:center;">
    <h2 style="font-family:HelveticaNeue-CondensedBold, Arial Narrow">Break blocks as much you can!</h2>
    <div>
      <p>A game by one-man indie game developer Son Gil</p>
      <a href="https://itunes.apple.com/us/app/duetblock/id1003050174?mt=8" title="go to appstore">
      <img src="/assets/img/badge_app_store.png" alt="Appstore" />
      </a>
    </div>
    <h2 style="font-family: HelveticaNeue-CondensedBold, Arial Narrow">Get the highest score to beat world competitor!</h2>
    <div class="" style="width:80%;height:400px;display:inline-block;">
		  <iframe style="width:100%;height:100%;" id="video" src="https://www.youtube.com/embed/FRiaFlOtQrs" frameborder="0" allowfullscreen=""></iframe>
	  </div>
  </div>

  <div>&nbsp;</div>
  <h2 style="font-family:HelveticaNeue-CondensedBold, Arial Narrow">Screenshots</h2>
  <div class="one-half-col">
  {% for screen in page.screens %}
    <div>
      <table>
        <tr><th>{{ screen.title }}</th></tr>
        <tr><td><img src="{{ screen.imgurl }}"></td></tr>
      </table>
    </div>
  {% endfor %}
  </div>

</div>
