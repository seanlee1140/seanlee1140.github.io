---
title: "Arcade Game Controller"
layout: single
author_profile: false
sidebar:
  nav: "project_sidebar"
excerpt: "A USB arcade game controller with 3D printed case & buttons."
header:
  teaser: /assets/MK5 iso.png
---

Created a personalized arcade game (Tekken) controller with 3D printed case & buttons. Used Arduino Uno with rewritten firmware in DFU mode to emulate a USB gamepad. Features hinged lid for easy access to electronics and swappable mechanical keyboard switches.

![Arcade Game Controller](/assets/MK5 iso.png)

A few design considerations to improve modifiability and 3D printing & assembly process:

1. **Swappable mechanical keyboard switches and buttons** - to ensure the buttons feel smooth, secure, and swappable, the buttons were designed to be press-fit into the switches, and the switches were designed to be press-fit into the button socket bases, using tolerances of 0.2 mm so that they can be pulled out by hand when needed. Meanwhile, the buttons were designed to be 0.4mm smaller in diameter than the button sockets for smooth press and release actions while having no visible gaps.

2. **Hinged lid for easy access to electronics** - the lid is hinged to allow for easy access to the electronics inside the controller. The hinged lid is designed to be snap-fit into the base, allowing for easy assembly of the controller. For secure but easy opening and closing of the lid, I used two latches that rely on the PLA's flexibility.