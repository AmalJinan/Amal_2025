---
layout: base
title: Amalś Github site
description: My index
author: John Mortensen, Vivian Ni, Bria Gilliam
image: /images/mario_animation.png
hide: false
---

<!-- Liquid: statements -->

<!-- Include submenu from _includes to top of pages -->
{% include nav/home.html %}
<!-- Concatenation of site URL to frontmatter image -->
{% assign sprite_file = site.baseurl | append: page.image %}
<!-- Has is a list variable containing mario metadata for sprite -->
{% assign hash = site.data.mario_metadata %}  
<!-- Size width/height of Sprite images -->
{% assign pixels = 256 %}

<!-- Embedded Cascading Style Sheet (CSS) rules, define how HTML elements look -->

## Investing in Your Technical Futures

> CSSE 1,2 prepares students for the AP Computer Science pathway. This course focuses on teaching the JavaScript programming language, object-oriented programming and inheritance, and developing algorithmic thinking skills. Through game development projects, students will engage in engineering skills, learn fundamentals of programming, work with data structures, and foster collaboration skills with their peers. Tech talks will be conducted by teachers to introduce concepts, provide guidance on tools, and support ideas to establish development requirements. By performing development and exploration, this course aims to raise students' awareness of the tremendous capabilities of computers and software engineering skills across various fields.

#### Home page Hack
<a href="[url](https://raw.githubusercontent.com/AmalJinan/Amal_2025/refs/heads/main/navigation/blogs.md)">blogs hack</a>


<script src="https://utteranc.es/client.js"
        repo="AmalJinan/Amal_2025"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous" async>
</script>
