---
layout: home
permalink: /posts/
class: posts
---

{% for post in site.posts %}
 <div class="post_tumb">
    <div class="img-container">
        <img src="{{site.baseurl}}{{post.image_src}}" alt="asd">
    </div>
    <div class="content">
        <p class="title">{{post.title}}</p>
        <p class="desc">{{post.description}}</p>
        <p class="author">{{post.author}}</p>
        <a href="{{site.baseurl}}{{post.url}}">Read more...</a>
    </div>
</div>
{% endfor %}	
 