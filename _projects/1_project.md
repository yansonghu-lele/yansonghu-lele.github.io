---
layout: page
title: Monocular GSO
description: Real-time Volumetric SLAM
img: assets/img/o3.gif
importance: 1
category: work
related_publications: true
---

The culmination fo my Master's work.

M-GSO is a real-time volumetric dense simultaneous localization and mapping system. It harness the synergy between the photometric SLAM system Direct Sparse Odometry (DSO) and 3D Gaussian Splatting to achieving a combination of speed, map quality, and memory efficiency unmatched by other dense SLAM systems.

DSO is currently under review for the 2025 IEEE International Conference on Robotics and Automation (ICRA)

Preprint avalaible at https://arxiv.org/abs/2409.13055 {% cite hu2024mgsomonocularrealtimephotometric %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/o0-d.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/o1-d.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/o2-d.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Examples of M-GSO running on the synthetic Replica dataset
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/MH01-d.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/MH03-d.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Examples of M-GSO running on the real-life EUROC MAV drone dataset
</div>
