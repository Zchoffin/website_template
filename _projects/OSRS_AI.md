---
title: "OSRS AI"
layout: gridlay
sitemap: false
permalink: /projects/osrs_AI
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
  <h2>Overview</h2>
  This project began as a final project for my ECE 593 machine learning class, but I wanted to expand its features and capabilities.
  My goal was to create a YOLOv4 algorithm that can classify ores within the video game of Old School RuneScape. This project was done in two stages, the first was utilizing open source software titled "Open Labeling", then a custom classification algorithm was made using the pretrained coco dataset to be modified for my classifications for output.
</div>

<div class="jumbotron">
  <h2>Open Labeling</h2>
  As an initial test, 70 images of various ores were gathered in the mining guild located within the game. Each image had 4-13 objects that were classified within the software. The 5 ores used for classification were Coal, Tin, Iron, Adamantite, and Mithril. Given the 3D nature of the game, mutiple images were taken of individual ores from all angles to be able to identify on the fly.

  <img src="/images/open_labeling.png" alt="Open Labeling" style="width:100%; height:auto;">

</div>

<div class="jumbotron">
  <h2>YOLOv4 Results</h2>
  <img src="/images/results_1.png" alt="Open Labeling" style="width:100%; height:auto;">
  <img src="/images/results_2.png" alt="Open Labeling" style="width:100%; height:auto;">
</div>

<div class="jumbotron">
  <h2>The Model in Action</h2>
  <style>
  .video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    padding-top: 25px;
    height: 0;
  }
  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  </style>

  <div class="video-container">
  <iframe src="https://www.youtube.com/embed/8UKoKw4EdXE?si=9IBhHuNQJprab0OC" frameborder="0" allowfullscreen></iframe>
  </div>
</div>
