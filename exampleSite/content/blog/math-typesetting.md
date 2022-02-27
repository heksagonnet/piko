---
author: Hugo Authors
title: Math Typesetting
date: 2019-03-08
description: A brief guide to setup KaTeX
tags: ["math","markdown", "css", "html", "themes"]
categories: ["themes", "syntax"]
math: true
ShowBreadCrumbs: false
---

Mathematical notation in a Hugo project can be enabled by using third party JavaScript libraries.

<!--more-->

In this example we will be using [KaTeX](https://katex.org/)

-   To enable KaTex globally set the parameter `math: true` in a project's configuration (`config.yml`)
-   To enable KaTex on a per page basis include the parameter `math: true` in content files

**Note:** Use the online reference of [Supported TeX Functions](https://katex.org/docs/supported.html)

### Examples

Inline math:
{{< rawhtml >}}

<p>
\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>

{{< /rawhtml >}}

Block math:

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
