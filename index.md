---
layout: default
title: Ryan's Finance Blog
description: It's an investing blog
---

# Hello, World!

Welcome to my [GitHub Pages](https://pages.github.com) site. This page is generated from an `index.md` file using the Jekyll static site generator.

## Features
* **Markdown Support**: Easy to write and format.
* **Jekyll Themes**: Professional styling without manual CSS.
* **Free Hosting**: Hosted directly from your GitHub repository.

## Get Started
To modify this page, edit the `index.md` file in your repository. For more advanced styling, you can select a theme in your [GitHub Repository Settings](https://github.com).

### Code Snippet Example
```javascript
console.log("GitHub Pages is live!");
```
#### Where are my posts

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




---
[Contact Me](mailto:example@email.com) | [View on GitHub](https://github.com)
