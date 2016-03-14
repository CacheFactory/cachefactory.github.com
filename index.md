---
layout: page
title: Welcome
---

<h1>
  About
</h1>
<a href="/about.html">About me</a><br>
<a href="https://www.facebook.com/eddieanderson86">Facebook profile</a>
<h1>
  Posts
</h1>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<h2>Minesweeper</h2>
<a href="https://github.com/CacheFactory/Minesweeper">Github page</a>
<div class="minesweeper"></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.8.3/underscore-min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/backbone.js/1.2.3/backbone-min.js"></script>
<script src="/assets/js/minesweeper-interface.js"></script>
<script src="/assets/js/minesweeper.js"></script>

<script>
  $(document).ready(function(){
    var gameView = new GameView({el: $('.minesweeper') });
    gameView.render();
  })
</script>



