---
title: "Post With Thumbnail"
date: 2026-06-04T22:30:00+03:30
description: "A sample post showing where thumbnail images go in Stack."
image: "cover.jpg"
categories: []
tags: ["example", "thumbnail"]
draft: false
math: false
toc: true
---

This sample post shows how thumbnails work in the Stack theme.

<!--more-->

## Where The Picture Goes

For a post thumbnail, put the image in the same folder as the post:

```text
content/post/post-with-thumbnail/
├── index.md
└── cover.jpg
```

Then add this line near the top of `index.md`:

```yaml
image: "cover.jpg"
```

You can also use the same image inside the post body:

![Sample thumbnail](cover.jpg)
