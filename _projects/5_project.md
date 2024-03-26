---
# assets/js/modal.js
layout: page
title: concept art
description: A compilation of some of my artwork. Clicking on them prompts a pop-up in higher-res. More organized folders coming soon!
img: assets/img/1.jpg
importance: 1
category: artwork
---

<div class="caption">
    These are a compilation of character pages I've made. Some are fanart, but most are original character designs!
</div>

<div class="row" id="gallery" data-toggle="modal" data-target="galleryModal">
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/girlband1.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/girlband1.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/girlband2.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/girlband2.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/girlband3.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/girlband3.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/band_chick.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/band_chick.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/ken_page.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/ken_page.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/bee_page.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/bee_page.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/moms.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/moms.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/pirate_page.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/pirate_page.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/character-art/samus_page.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/samus_page.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
</div>

<div class="caption">
    Compiled sketches and studies.
</div>
<div class="row" id="gallery" data-toggle="modal" data-target="galleryModal">
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/widow.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/widow.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/daisy.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/daisy.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/medusa_bust.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/medusa_bust.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/bg3_bust.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/bg3_bust.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/peach_sketch.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/peach_sketch.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
    <div class="col-md-3 col-sm-4 col-6 py-2">
        <a href="#gallery-modal" data-large-src="/assets/img/sketches/pharah_sketch.png" data-toggle="modal" class="image-data">
            <img src="/assets/img/thumbnails/pharah_sketch.png" class="w-100 shadow-1-strong rounded mb-4">
        </a>
    </div>
</div>


<!-- Modal -->
<div class="modal fade" id="gallery-modal" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
    <div class="modal-content">
      <div class="modal-body">
        <img src="//placehold.it/1200x700/222?text=..." class="loaded-image mx-auto img-fluid" class="modal-img" alt="modal img">
      </div>
    </div>
  </div>
</div>

<script>
   document.addEventListener("click", function (e) {
    if(e.target.parentElement.classList.contains("image-data")) {
        const src = e.target.parentElement.getAttribute("data-large-src");
        document.querySelector(".modal-img").src = src;
        const myModal = new bootstrap.Modal(document.getElementById('gallery-modal'));
        myModal.show();
    }
    else {
        document.querySelector(".modal-img").src = "//placehold.it/1200x700/222?text=...";
    }
 });
</script>

