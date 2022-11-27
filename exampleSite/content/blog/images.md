---
author: "Hugo Authors"
title: "Adding Images"
date: "2022-03-05"
description: "Guide to adding images in Piko theme"
tags: ["images","markdown", "css", "html", "themes"]
categories: ["themes", "syntax"]
ShowRelated: false
showToc: false
ShowBreadCrumbs: false
---

To add images you can use the following syntax:
```md
![This where you put the alt information](/uploads/self.webp)
```

![This where you put the alt information](/uploads/self.webp)

To add title, use the following syntax (`<figure>` element will be generated with `<figcaption>`):
```md
![This where you put the alt information](/uploads/self.webp "This is where you put the title")
```

![This where you put the alt information](/uploads/self.webp "This is where you put the title")

Or from external sources:

```md
![This is where you put the alt](https://images.unsplash.com/photo-1520085601670-ee14aa5fa3e8 "This is the image title")
```

![This is where you put the alt](https://images.unsplash.com/photo-1520085601670-ee14aa5fa3e8 "This is the image title")