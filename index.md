---
layout: page
title: 追随大神的脚步
tagline: Keep on line
---
{% include JB/setup %}


<div class="posts-list">
    <h3>文章列表</h3>
    <ul class="posts">
        {% for post in site.posts %}
            <li><span>{{ post.date | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    </ul>
</div>
