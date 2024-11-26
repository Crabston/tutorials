---
title: Hadron Tutorials
slug: hadron
blog_url: /hadron
sitemap:
  changefreq: monthly
  priority: 0.9
  lastmod: 10-10-2024
date: 10-10-2024
taxonomy:
  author: Crabston GmbH
  category: [ Tutorial Page ]
feed:
  limit: 10
hero_classes: 'text-light overlay-dark-gradient hero-large parallax'
body_classes: 'header-dark header-transparent'
show_breadcrumbs: false
sidebar:
  show_popular_tags: true
  show_feed: true
  show_toc: false
  show_tntsearch: true
pagination: true
show_pagination: true
bricklayer_layout: true
child_type: item
display_post_summary:
  enabled: false
modular_content:
  items: '@self.modular'
  order:
    by: folder
    dir: dsc
    custom:
      - _nachricht
content:
	# TODO: use '@self.children' instead of '@self.descendants' when the blog is ready
	# needs bugfix of empty tags getting displayed
  items: '@self.descendants'
  limit: 8
  order:
    by: date
    dir: dsc
  pagination: true
  url_taxonomy_filters: true
hide_summary: true
---

This collection of tutorials is specific to using the Hadron Theme & Skeleton for Grav CMS. Other themes and skeletons have different requirements and features and may not work with these tutorials.

===

# Hadron Tutorials
## Guides for the Hadron Theme & Skeleton

This collection of tutorials is specific to using the Hadron Theme & Skeleton for Grav CMS. Other themes and skeletons have different requirements and features and may not work with these tutorials.
