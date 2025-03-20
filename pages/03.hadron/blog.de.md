---
title: Hadron
slug: hadron
blog_url: /hadron
sitemap:
  changefreq: monthly
  priority: 0.9
  lastmod: 06-10-2024
date: 06-10-2024
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

Diese Sammlung von Anleitungen sind spezifisch für das Benutzen des Hadron Grav Skeleton und/ oder das Hadron Grav Theme. Hadron ist ein Child-Theme von Quark und bietet viele zusätzliche Funktionen und Anpassungsmöglichkeiten.

===

# Hadron Tutorials
## Anleitungen zum Hadron Grav Skeleton & Grav Theme

Diese Sammlung von Anleitungen sind spezifisch für das Benutzen des Hadron Grav Skeleton und/ oder das Hadron Grav Theme. Hadron ist ein Child-Theme von Quark und bietet viele zusätzliche Funktionen und Anpassungsmöglichkeiten.
