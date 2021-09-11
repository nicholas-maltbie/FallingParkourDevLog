---
layout: post
title:  "Update: Conveyer Belts"
date: 2021-09-10 21:15:00 0000
modified_date: 2021-09-10 21:15:00 0000
categories: update
author: "Nick Maltbie"
image: "assets/post-preview/belts-update-preview.png"
video: "https://www.youtube.com/v/nkHLHcRzOv0"
comments: true
---

Weekly post number 5, development this week was a little slower due to other commitments but have lots of fun updates
nonetheless. You can download the current version of the project
[v0.0.33 for Windows](https://drive.google.com/file/d/1n1RM55WswLBPDHWdwFsygg0ZvLLG2C11/view?usp=sharing)
if you want to check out the changes for yourself. 

* TOC
{:toc}

# Change List

Here is a video summary of the changes added to the project. 
<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/nkHLHcRzOv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Here is the list of changes added to the project since last week:
* **[v0.0.30](https://github.com/nicholas-maltbie/FallingParkour/pull/37)** Switched some of the existing obstacles to
  now be kinematic objects (will talk about this more in a future short video). 
* **[v0.0.31](https://github.com/nicholas-maltbie/FallingParkour/pull/38)** Upgrade the unity version used to make and
  edit the project. 
* **[v0.0.32](https://github.com/nicholas-maltbie/FallingParkour/pull/39)**
  Converted from Mirror Networking to Unity's MLAPIfor multiplayer backend library.
* **[v0.0.33](https://github.com/nicholas-maltbie/FallingParkour/pull/40)** 
  Added Conveyer belt obstacles to the project.

# Feature Highlight - Conveyer Belts!

![View of player walking across conveyer belts in the latest update]({{ site.baseurl }}/assets/images/belts-update/belts-image.jpg)

This week we added a new kind of obstacle to the game: conveyer belts. When a player stands on these belts, they will be
moved along at a constant rate whichever way the belt is pointing. This includes moving the player up slopes, forward,
backward, or wherever the belt is directed. These belts will be the new centerpiece of the next planned level: Factory.
This factory level will have all sorts of conveyer belts, moving gears, and other large obstacles that players will have
to navigate through to be the first to reach the end of the map!

These belts are made of a scrolling texture that moves an image of arrows across the belts surface. Making these belts
in the 3d modeling software Blender was an interesting process. I had to make sure that I could have the belt scroll at
the same speed it moved the player. I made sure the entire length of the belt was 16 units long (including the curved
edges) then tiled an arrow texture 16 times and had it move forward at a rate of 1 unit per second. This way the belt
would translate forward at a rate of 1 unit per second and the player would move at a speed of one unit per second when
standing on the belt. 

# Post Progress - Hidden Paths

Using the hexagon code and some fading code from the character model, I'm working on making another map of hidden tiles
similar to the round Tip Toe from Fall Guys or the level where players need to follow a hidden map from Pummel Party.
The idea behind this level will be that the floor is hidden some of the time and will appear at regular
intervals. Players will either need to remember the path to the next tiles or wait for the path to re-appear every few
seconds when reaching the end of the maze. The path finding code from the previous post will be quite useful in
achieving these goals!

Below is an example of what these tiles look like when they fade in and out.

![Animation of hexagon tiles fading in and out]({{ site.baseurl }}/assets/images/belts-update/hex-grid-fade-5.gif)

# Future Plans

Crossed quite a few things off the list of things to do. These are a few of the times items we’ve achieved since last
week:
* Some new assets and features for existing maps!

Not sure which tasks will be prioritized right away, but these are the current plans for the game:
* End a round once all players have finished (instead of waiting for timer to end)
* Improving models and textures, polishing existing maps
* Score screen to show player scores at the end of round
* Improvement to character controller
    * Slippery ground to slide across
    * Diving forward after jumping
    * Bouncy surfaces and objects to jump off
    * Rag-doll animation for player when they are prone
    * Always more debugging...
* More game sound effects and music

Can't wait to get started on those next features.

Have a great week

\- _Nick Maltbie_
