---
layout: post
category: [메롱]
title: "5. GitHub 블로그에 Category 만들기"
---

# 카테고리 만드는데 참고한 사이트들 
1. [요기](https://devyurim.github.io/development%20environment/github%20blog/2018/08/07/blog-6.html)
2. [여기](http://blog.knowgari.com/make-category/#categories-%ED%8F%B4%EB%8D%94%EC%97%90-index-%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%83%9D%EC%84%B1%ED%95%98%EA%B8%B0)

---

처음에 저 사이트들을 참고해도 해결 되지 않아서 ~~늪에 빠지고 있었는데~~ `_data/archive.yml` 에 들어가보니 

```
- type: dates
  title: Dates
  url: /dates/
#- type: categories
#  title: Categories
#  url: /categories/
- type: tags
  title: Tags
  url: /tags/
```
이렇게 categories들이 주석 처리가 되어있었더라구요. 
앞에 # 들을 지우고, 위 블로그 들을 참고하니 카테고리가 생성되었습니다.
