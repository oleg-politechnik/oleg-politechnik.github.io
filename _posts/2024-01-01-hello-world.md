---
layout: post
title: Hello, World!
categories: [Blogging, Website]
tags: [again what learned, web development]
date: 2024-01-01 17:30 +0100
toc: false
---

### Welcome to my first post on my first own website!

Recently, I faced the task of creating a simple website with the smallest possible maintenance overhead.
After conducting some research, I stumbled upon GitHub Pages for hosting and was convinced by the Jekyll static site generator.

[This video](https://youtu.be/F8iOU1ci19Q) also saved me a ton of time searching for the proper [Jekyll](https://jekyllrb.com/) theme ([Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)).

Extra points in my eyes for the GitHub Pages/Jekyll/Chirpy stack:
- It is easy to set up locally and does not require in-depth knowledge of Ruby.
- It boasts a minimalistic and adaptive design, supporting both desktop and mobile layouts.
- It automatically adjusts to the client's dark/light mode system preference (with a manual option available).
- The local development instance supports the automatic reload of the website's browser tab upon changing website source files (`bundle exec jekyll serve --livereload`).
- It correctly manages client-side caching for a production website, including a popup notification of a new version available.
- It enjoys good availability from one of the established industry names (github.com).
- No need to worry about security patches or TLS certificate management for HTTPS.
- Out of the box, there's automatic deployment via GitHub Actions upon pushing to the main branch.
- It handles all the HTML/CSS markup (View), allowing the website admin to focus primarily on the Markdown (Model).
- For more advanced uses, it offers the Liquid templating engine, which looks familiar due to its striking similarity to Jinja2.

Stay tuned!

![Sky](/assets/images/sky_is_the_limit.jpeg){: .w-50 .center }
