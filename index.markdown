---
layout: Main page # 또는 다른 적절한 레이아웃 이름
title: "나의 메인 페이지"
---

## 환영합니다!

이곳은 저의 블로그 메인 페이지입니다.
최신 게시물을 아래에서 확인해 보세요!

{% assign posts = site.posts | sort: "date" | reverse %}
{% for post in posts limit: 5 %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
{% endfor %}