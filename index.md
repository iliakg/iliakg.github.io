---
layout: default
---

<div id="posts">

  {% for post in site.posts %}
    {% include _post.html item=post %}
  {% endfor %}

</div>
