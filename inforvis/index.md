---
layout: home
---

<div class="index-content inforvis">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/"><span>post</span></a></li>
            <li class="on" style="text-align:center"><a href="/inforvis"><span>inforvis</span></a></li>
            <li style="text-align:right"><a href="/portfolio"><span>portfolio</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.inforvis %}
            <li>
                <h2>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
