---
layout: page
permalink: /photography/
title: photography
description: A personal collection of photographs.
nav: true
nav_order: 6
images:
  venobox: true
---

<style>
  .photo-intro {
    max-width: 640px;
    margin: 0 0 3rem 0;
    font-size: 1.05rem;
    line-height: 1.7;
    opacity: 0.8;
  }

  .photo-grid {
    column-count: 1;
    column-gap: 1.25rem;
  }

  @media (min-width: 576px) {
    .photo-grid { column-count: 2; }
  }

  @media (min-width: 992px) {
    .photo-grid { column-count: 3; }
  }

  .photo-item {
    display: block;
    break-inside: avoid;
    margin-bottom: 1.25rem;
    position: relative;
    overflow: hidden;
  }

  .photo-item img {
    display: block;
    width: 100%;
    height: auto;
    transition: transform 0.6s cubic-bezier(0.22, 1, 0.36, 1), filter 0.6s ease;
    filter: grayscale(6%);
  }

  .photo-item:hover img {
    transform: scale(1.035);
    filter: grayscale(0%);
  }

  .photo-caption {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    padding: 0.9rem 1rem;
    font-size: 0.8rem;
    letter-spacing: 0.02em;
    color: #fff;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.55), rgba(0, 0, 0, 0));
    opacity: 0;
    transform: translateY(6px);
    transition: opacity 0.35s ease, transform 0.35s ease;
    pointer-events: none;
  }

  .photo-item:hover .photo-caption {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<p class="photo-intro">
  A few frames from the places I've passed through — mostly shot on quiet walks, somewhere between fieldwork and everywhere else.
</p>

<div class="photo-grid">
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/01.jpg">
    <img src="/assets/img/photography/01.jpg" alt="Photograph 01" loading="lazy">
    <span class="photo-caption">01</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/02.jpg">
    <img src="/assets/img/photography/02.jpg" alt="Photograph 02" loading="lazy">
    <span class="photo-caption">02</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/03.jpg">
    <img src="/assets/img/photography/03.jpg" alt="Photograph 03" loading="lazy">
    <span class="photo-caption">03</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/04.jpg">
    <img src="/assets/img/photography/04.jpg" alt="Photograph 04" loading="lazy">
    <span class="photo-caption">04</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/05.jpg">
    <img src="/assets/img/photography/05.jpg" alt="Photograph 05" loading="lazy">
    <span class="photo-caption">05</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/06.jpg">
    <img src="/assets/img/photography/06.jpg" alt="Photograph 06" loading="lazy">
    <span class="photo-caption">06</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/07.jpg">
    <img src="/assets/img/photography/07.jpg" alt="Photograph 07" loading="lazy">
    <span class="photo-caption">07</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/08.jpg">
    <img src="/assets/img/photography/08.jpg" alt="Photograph 08" loading="lazy">
    <span class="photo-caption">08</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/09.jpg">
    <img src="/assets/img/photography/09.jpg" alt="Photograph 09" loading="lazy">
    <span class="photo-caption">09</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/10.jpg">
    <img src="/assets/img/photography/10.jpg" alt="Photograph 10" loading="lazy">
    <span class="photo-caption">10</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/11.jpg">
    <img src="/assets/img/photography/11.jpg" alt="Photograph 11" loading="lazy">
    <span class="photo-caption">11</span>
  </a>
  <a class="photo-item venobox" data-gall="photography" href="/assets/img/photography/12.jpg">
    <img src="/assets/img/photography/12.jpg" alt="Photograph 12" loading="lazy">
    <span class="photo-caption">12</span>
  </a>
</div>
