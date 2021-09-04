---
layout: post
title:  "Update: Wipeout"
date: 2021-09-02 22:25:00 0000
modified_date: 2021-09-02 22:25:00 0000
categories: update
author: "Nick Maltbie"
image: "assets/post-preview/wipeout-update-preview.png"
video: "https://www.youtube.com/v/HJhNoDgmxUU"
comments: true
---

Weekly post number 4, a full month of updates so far! The development of the project has been going great and there are
so many new and fun updates to talk about this week! You can download a copy of the project from this week’s development
[v0.0.29 for windows](https://drive.google.com/file/d/1DWAvXPaDGaUKYqetAFBEqMVZ-aHcrfWS/view?usp=sharing). Lots of
things to talk about for this week, so let’s hop right in.

* TOC
{:toc}

# Change List

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/HJhNoDgmxUU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Here is the list of changes added to the project since last week:
* **[v0.0.24](https://github.com/nicholas-maltbie/FallingParkour/pull/31)** Updating jittery movement on oddly-shaped,
  spinning floors. 
* **[v0.0.25](https://github.com/nicholas-maltbie/FallingParkour/pull/32)** Updated configuration for the Big Fans and
  Hex-A-Gone game modes. 
* **[v0.0.26](https://github.com/nicholas-maltbie/FallingParkour/pull/33)** Improved default mouse sensitivity.
* **[v0.0.27](https://github.com/nicholas-maltbie/FallingParkour/pull/34)** Updated multiplayer library in project. 
* **[v0.0.28](https://github.com/nicholas-maltbie/FallingParkour/pull/35)** Fixed player movement on curved fans (for
  real this time).
* **[v0.0.29](https://github.com/nicholas-maltbie/FallingParkour/pull/36)** Two additions for this update:
    * Added ability for character to be knocked rag-doll.
    * Added a new map: Wipeout.

# Feature Highlight - Wipeout

![View of the wipeout map from above. There is a disk with the center cut out and two long arms sticking out of a
central cylinder which goes through the hole in the disk.]({{ site.baseurl }}/assets/images/wipeout-update/sample-overview.jpg)

The feature highlight this week is the new level: Wipeout. This ties in with a new key feature that was added with this
most-recent version as well: rag-doll animations! This level is inspired from Fall Guys: Ultimate Knockout’s [Jump
Club](https://fallguys.com/rounds/jump-club) round. The map mainly consists of a central disk that has a hole cut out of
the center and two arms that spin around. The two arms are spread out so that one is at the level of the player and the
other one is above the player’s head. Players will have to expertly jump through the level to stop the arms from
flinging them off the edge of the map. 

![View of the wipeout map from above. There is a disk with the center cut out and two long arms sticking out of a
central cylinder which goes through the hole in the disk.]({{ site.baseurl }}/assets/images/wipeout-update/sample-doge.jpg)

In order to have this work, I needed to make a big change to the game: knocking the player prone. I say prone but it
really is just allowing the character player to move as a dynamic object. This means that whenever the player hits
something on the map, they turn into a rag-doll and start rolling around the map.

In the case of this level, whenever the arms hit the player, the player will turn into a dynamic object and start
rolling around the map. Above, you can see a picture of a player diving over the bottom bar and being hit, causing them
to fall down onto the ground. This feature makes the game look much more dynamic and has the potential to add quite a
few new levels of challenge to the map.

# Post Progress - Hex-A-Gons are the Best-A-Gons

![Animation path finding in a hexagon grid]({{ site.baseurl }}/assets/images/wipeout-update/hexagon-progress.gif)

Last week I promised to make an update about the hexagons. I have a small update. Above is the current progress picture
of creating new hexagon grid maps. The github project with the code is found here:
[https://github.com/nicholas-maltbie/TileMaps](https://github.com/nicholas-maltbie/TileMaps). I will be updating it to
include a lot more features for tile maps of any type and all sorts of fun path finding and interesting tricks. This
might be used in new game modes that use hexagon or grid maps as part of the terrain. It might take me a few weeks, but
I’ll do my best to keep adding features and eventually build to releasing a Unity package with the recolor shader.

# Future Plans

Crossed quite a few things off the list of things to do. These are a few of the times items we’ve achieved since last
week:
* Improvement to character controller
    * Knocking the character prone/rag-doll
*	New maps!

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
