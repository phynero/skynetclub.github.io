---
layout: page
title:  "skynet sites"
date:   2015-08-06 16:03:19
categories: skynet
tags: [skynet]
---

<div class="home">

  <h1 class="page-heading">相关网站</h1>


      <ul class="post-list">
        {% for link in site.data.sites %}
          <li>
            <h3>
              <a class="post-link" href="{{ link.url }}">{{ link.name }}</a>
            </h3>
            <span class="post-meta">{{ link.desc }}</span>
          </li>
        {% endfor %}
      </ul>
        
  
  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>