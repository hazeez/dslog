---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}

# post thumb - set only one image
#image: "images/featured-post/post-1.jpg"
image: "images/post/post-3.jpg"
image_credit: "a sample post picture"
thumbnail: "images/post/post-3.jpg"
alt: "test image"

# meta description
description: "this is meta description"

# taxonomies
# use only one category; tags can be multiple
categories: 
  - "Cat1"
tags:
  - "tag1"
  - "tag2"

# post type - 'featured' or 'post' or 'hidden'
type: "featured"

# set the slug for the post
slug: "test-slug"

# keywords
keywords:
- technology

# comments - set to 'true' or 'false'
comments: false

showMeta: false
showActions: false

# draft post or not - set 'true' or 'false'
draft: true

#funfact
funfact: true
funfact_description: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam nihil enim maxime corporis
cumque" 

# sidebar display
show_sidebar: true

---

