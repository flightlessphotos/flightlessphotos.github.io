---
layout: page
title: Kids Personality Photography
permalink: /personality
accordion: 
  - title: This is item 1
    content: something about preparing kids goes here.
  - title: this is item 2
    content: how to get the best photos
---
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/blocks.css">
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/imgboxrows.css">


<div class="white-block">
Kids grow up so fast! Let's create a timeless keepsake showcasing who they are right now. Instead of fake smiles or awkward poses like you get from school photos, I capture your child just being themselves - whether they are silly, shy, or full of energy!
</div> <!-- end white-block -->

<div class="white-block">
{% include accordion.html %}
</div> <!-- end white-block -->

{% include image-gallery.html folder="/assets/img/examples/personality" %}

<!-- Image Gallery / Lightbox Content. These go at the footer of the page. -->
<script type="text/javascript" src="/assets/js/lightbox.js"></script>
<link rel="stylesheet" href="/assets/css/lightbox.css">
