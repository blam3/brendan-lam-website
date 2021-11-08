---
title: My Blog
description: |
  My blog where I share my thoughts on psychology, research methods, and things that wouldn't get past peer review. I'm a novice on many of these topics, so this platform lets me share my thoughts without the pressure of having to be right. Although, I try my best to do that and am always open to feedback.
author: "Brendan Lam"
show_post_thumbnail: true
show_author_byline: true
show_post_date: true
# for listing page layout
layout: list-sidebar # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: p = 0.49
  description: |
    A blog where I share my thoughts on psychology, research methods, and things that wouldn't get past peer review. I'm a novice on many of these topics, so this platform lets me share my thoughts without the pressure of having to be right. Although, I try my best to do that and am always open to feedback.
    
    Check out the _index.md file in the /blog folder 
    to edit this content. 
  author: "The R Markdown Team @RStudio"
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "Brendan Lam"
  show_author_byline: true
  show_post_date: true
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /blog/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
