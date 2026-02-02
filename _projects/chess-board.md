---
title: "Chess.com Integrated Automatic Chess Board"
layout: single
author_profile: false
sidebar:
  nav: "project_sidebar"
excerpt: "Description of project 2."
---

This project is essentially a controller for a game of chess on chess.com; it is a physical board that is synchronised with an online game of chess on chess.com. 


## High-Level Design Overview
When a user makes a move on the physical board, the move is detected with a mesh of hall effect sensors and sent to the software that plays that move on chess.com by simulating mouse clicks. 

Similarly, when an opponent makes a move on chess.com, the move is detected  by the software and sent to the microcontroller that replicates that move on the physical board with a hidden gantry system underneath the board. The gantry system moves to the starting square, attaches to the piece with a magnet at the end of a linear actuator, then moves to the destination square and releases the piece. 
![High-Level Design Overview](/assets/chessboard_data_infrastructure.png)

