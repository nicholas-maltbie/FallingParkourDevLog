---
layout: post
title:  "Update: The Factory"
date: 2021-09-18 00:00:00 0000
modified_date: 2021-09-18 00:00:00 0000
categories: update
author: "Nick Maltbie"
image: "assets/post-preview/the-factory-preview.png"
video: "https://www.youtube.com/v/bkntMp7f_Nk"
comments: true
---

Weekly post number 5, development this week was a little slower due to other commitments but have lots of fun updates
nonetheless. You can download the current version of the project
[v0.0.35 for Windows](https://drive.google.com/file/d/1gAwE318hUj37g8UQc5mrjFMQshzhbnDy/view?usp=sharing)
if you want to check out the changes for yourself. 

* TOC
{:toc}

# Change List

Here is a video summary of the changes added to the project. 
<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/bkntMp7f_Nk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Here is the list of changes added to the project since last week:
* **[v0.0.34](https://github.com/nicholas-maltbie/FallingParkour/pull/44)** Experimental conveyer belt changes for
  animated texture maps.
* **[v0.0.35](https://github.com/nicholas-maltbie/FallingParkour/pull/41)** Starting building the new Factory map. Also
  added the ability of the player to push objects.

# Feature Highlight - The Factory!

As discussed in the video above, the new factory map has been added. It's still a work in progress but has three main
sections now:
1. A set of conveyer belts the players must traverse and doge fast moving gears.
2. Rotating gears players must navigate through.
3. A set of push-able boxes that players must shove over to reach the end.

I'm looking forward to adding new elements such as moving platforms the player need to jump between and throwing more
objects at players to knock them on the ground. Comment if you have any suggestions for what else to add to the level. 

# Explained - Conveyer Belts!

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/EypvlRUQwKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

This week, I added kicked off the new Explained series on my YouTube channel where I will take an asset from my project
and convert it into its own repo. In addition, I will make a short video explaining how the asset was developed and what
challenges I faced along the way. Hopefully next week I will be abel to make an explained video about the Recolor
Shader!

# Future Plans

Crossed quite a few things off the list of things to do. These are a few of the times items we’ve achieved since last
week including adding a new map and debugging some KCC features (pushing objects around). 

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
