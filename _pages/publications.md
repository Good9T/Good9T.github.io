---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<div class="wordwrap">**Multi-Type Attention for Solving Multi-Depot Vehicle Routing Problems**, Jinqi Li, Bing Tian Dai, Yunyun Niu, Jianhua Xiao, Yaoxin Wu, *IEEE Transactions on Intelligent Transportation Systems*, 2024 (Accept) [Code&Paper](https://github.com/Good9T/MD_MTA))</a>.</div>
<div class="wordwrap">**Solving pick-up and delivery problems via deep reinforcement learning based symmetric neural optimization**, Jinqi Li, Yunyun Niu, Guodong Zhu, Jianhua Xiao, *Expert Systems with Applications*, 2024 (Accept) [Code&Paper](https://github.com/Good9T/PD-SNO)</a>.</div>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
