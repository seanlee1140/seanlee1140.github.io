---
title: "Litter Pickup Drone"
layout: single
author_profile: false
sidebar:
  nav: "project_sidebar"
excerpt: "Semi-autonomous drone that picks up litter from trails."
header:
  teaser: /assets/3-prong claw.png
gallery:
  - url: /assets/3-prong claw.png
    image_path: /assets/3-prong claw.png
    alt: "3-prong claw"
  - url: /assets/Capstone_Bent_Prong.jpg
    image_path: /assets/Capstone_Bent_Prong.jpg
    alt: "Bent Prongs"
---

Developed as a capstone project of my undergraduate degree in Mechatronics Engineering at the University of British Columbia, this project involved the design and development of a semi-autonomous drone that can pick up litter from trails. It is currently ongoing.

## High-Level Design Overview

The client envisions a drone that can autonomously fly to a user-identified litter location, pick up the litter, and return to the user for drop-off. As a first step towards this vision, our team is developing a drone that can be manually controlled to perform said task.

## Pickup Mechanism

We have considered a variety of pickup mechanisms, and the 3-pronged claw mechanism that I designed has been selected. Using a set of custom designed central worm gear and helical gears, this mechanism converts simple rotation input from a DC motor to opening/closing a claw. Inspired by a gripper mechanism by Festo, each of the TPU-printed prongs bend upon coming in contact with an object, allowing the claw to grip onto the object more securely. 


<style>
  .fixed-height-gallery img {
    height: 300px; /* Fixed height for all images */
    object-fit: contain; /* Resize keeping ratio */
    width: 100%;
  }
</style>

{% include gallery class="fixed-height-gallery" %}