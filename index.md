---
title: Blogging Like a Hacker
---

{% for post in site.posts %}
<md-card>
  <md-card-header>
    <div class="md-title">{{ post.title }}</div>
  </md-card-header>
  <md-card-actions>
    <md-button href="{{ post.url }}">Read More</md-button>
  </md-card-actions>
  <md-card-content>
    {{ post.excerpt }}
  </md-card-content>
</md-card>
{% endfor %}

