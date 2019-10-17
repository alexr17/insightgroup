---
title: About
layout: page
---
<!-- <div class="footer-main"></div> -->

<div class="row">
  <div class="col-sm-6">
    <div class="card border-0">
      <!-- <img class="card-img-top" src="..." alt="Card image cap"> -->
      <div class="card-body">
        <h3 class="card-title">Our Story</h3>
        <p class="card-text">{{ site.about.history }}{{ site.about.now }}</p>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card border-0">
      <!-- <img class="card-img-top" src="..." alt="Card image cap"> -->
      <div class="card-body">
        <h3 class="card-title">Our Mission</h3>
        <p class="card-text">{{ site.about.mission }}</p>
      </div>
    </div>
  </div>
</div>

![Kellogg Image]({{ site.url }}/{{ site.kellogg }})

<div class="row">
  <div class="col-sm-12">
    <div class="card border-0">
      <!-- <img class="card-img-top" src="{{site.url}}/{{site.kellogg}}" alt="Kellogg Image"> -->
      <div class="card-body">
        <h3 class="card-title">A message from El Presidentè</h3>
        <p class="card-text">{{ site.about.henry_quote }}</p>
      </div>
    </div>
  </div>
</div>