---
date: {{ .Date }}
title: {{ replace .File.ContentBaseName `-` ` ` | title }}
slug:
description: Page description.
author: Steve
draft: true
cover:
 image: img/quad1-720px.jpg
 alt: alt text here
 caption: Quad in Winter

tags:

 - tag 1
 - tag 2
 - tag 3

categories:
 - cat 1
 - cat 2
---

post text here


{{< youtube 1111111 >}}