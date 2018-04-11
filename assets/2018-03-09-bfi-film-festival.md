---
layout: project
title:  "BFI film festival"
size:   "large"
type:	"brochure"
img:    bfi-featured.jpg
thumb:	wide-32.jpg
alt:	Poster brochure for a Hitchcock themed film festival. 
gallery:
  - bfi-website-page.jpg
  - bfi-website-styles.jpg
  - bfi-badges.png
  - bfi-popcorn.png
  - bfi-poster.jpg
  - bfi-tickets.png
  - bfi-brochure-cover.png
  - bfi-brochure-inside.png
---
Design a brochure and the rollout for the Hitchcock film festival at the British Insitute of Film.

<div class="gallery">
	{% for img in page.gallery %}
	  	<img src="{{ site.baseurl }}/images/hitchcock/{{ img }}" alt="">
	{% endfor %}
</div>

<!--
<video controls>
	<source src="{{ site.baseurl }}/images/itraya-spaghetti.mp4" type="video/mp4">
    <a href="{{ site.baseurl }}/images/itraya-spaghetti.mp4" class="player"><p>Itriya Spaghetti</p></a> 
</video>
-->