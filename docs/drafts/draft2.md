---
layout: docs
permalink: /docs/about/draft2/
title: Draft
---




{% include tabs.html heading1="MAC" text1="she is an amazing comic" heading2="WINDOWS" text2="she has been harrassed on twitter" heading3="LINUX" text3="she stars in this movie as a subway worker" %}


{% include_relative whatever.md %}

<div>

  <!-- Nav tabs -->
  <ul class="nav nav-tabs" role="tablist">
    <li role="presentation" class="active"><a href="#home" aria-controls="home" role="tab" data-toggle="tab">{% svgicon apple %} MAC</a></li>
    <li role="presentation"><a href="#whatever" aria-controls="whatever" role="tab" data-toggle="tab">{% svgicon windows %} WINDOWS</a></li>
    <li role="presentation"><a href="#horse" aria-controls="horse" role="tab" data-toggle="tab">{% svgicon linux %} LINUX</a></li>  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="home">This is s a home text</div>
    <div role="tabpanel" class="tab-pane" id="whatever">{% include_relative whatever.md %}</div>
    <div role="tabpanel" class="tab-pane" id="horse">a horse is not a zebra</div>
   </div>

</div>


Why use Github?
Explanation [here](http://blog.okfn.org/2013/07/02/git-and-github-for-data/) on a case of git and github for data by the okfn.


---
