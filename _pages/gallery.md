---
layout: page
permalink: /gallery/
title: Pictures from the lab and field
nav: false
images:
  lightbox2: true
_styles: |
  .post-header {
    text-align: center;
  }
  div.container.mt-5 {
    max-width: 870px;
  }
  .photo-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
    gap: 1rem;
  }
  .photo-gallery a {
    display: block;
    aspect-ratio: 4 / 3;
    overflow: hidden;
    border-radius: 0.25rem;
  }
  .photo-gallery img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.2s ease;
  }
  .photo-gallery a:hover img {
    transform: scale(1.03);
  }
---

<div class="photo-gallery">
  {% for photo in site.data.gallery %}
    <a href="{{ photo.image | relative_url }}" data-lightbox="research" data-title="{{ photo.caption | escape }}">
      <img src="{{ photo.image | relative_url }}" alt="{{ photo.alt | default: photo.caption | escape }}" loading="lazy">
    </a>
  {% endfor %}
</div>
