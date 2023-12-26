---
title: "Ghost"
author: ghost
layout: page
image: 
  thumbnail: /images/authors/ghost/profile.png
excerpt_separator: <!--end_excerpt-->
---

## Ghostwriter

{% include page-author.html %}

<!--end_excerpt-->

***

Placeholder auteur voor wanneer de credits naar een ander moeten worden toegeschreven

## De collectie
* Empty...

## Grail piece
Een "Skeleton"-piece

## Tot slot
Dit profiel is meer ter opvulling

<h3><p style="text-align: center;">Welkom op <a href="/">DikkeKlok.nl</a></p></h3>

<!-- author posts -->
{% assign filtered_posts = site.posts | where: 'author', page.author %}
{%- for entry in filtered_posts -%}
    {% include entry.html %}
{%- endfor -%}