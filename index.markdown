---
layout: default
---

Farsky is a hybrid decentralized social platform combining the best of Bluesky/ATProto and Farcaster.

## Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>