---
layout: post
title:  "Hello, world!"
categories: [ blogging ]
tags: [ test ]
image: assets/images/qilip_nebula.jpg
---
블로그 테스트!

# H1

## H2

### H3

#### H4

#### YAML front matter.

featured post - featured:true
exclude featured post from “All stories” loop to avoid duplicated posts - hidden:true
post image - image: assets/images/mypic.jpg
external post image - image: "https://externalwebsite.com/image4.jpg"
page comments - comments:true
meta description (optional) - description: "this is my meta description"

```html
---
layout: post
title:  "제목"
categories: [ 카테고리 ]
tags: [ 태그 ]
image: assets/images/이미지_이름.jpg
description: "글 설명"
featured: true
hidden: true
rating: 4.5
beforetoc: "toc 전에 나올 글"
toc: true
---
```

#### 스포일러 방지 사용법

<span class="spoiler">스포일러가 되는 내용을 여기에</span>
```html
<span class="spoiler">스포일러가 되는 내용을 여기에</span>
```
