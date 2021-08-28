---
layout: post
title:  "Update: Hex-A-Gone"
date: 2021-08-26 22:25:00 0000
modified_date: 2021-08-26 22:25:00 0000
categories: update
author: "Nick Maltbie"
image: "assets/post-preview/hexagons-update-preview.png"
video: "https://www.youtube.com/v/Aivqvz2u7js"
comments: true
---

Weekly post number 3!!! Lots of new features added this week and plenty of bug cleaning as well. Overall, the feature
additions and changes are coming along quite smoothly. You can download a copy of the project form this week's
development [v0.0.23 for windows](https://drive.google.com/file/d/1DFX6879WyvreJAx1T0dV9iY8IweJpzXT/view?usp=sharing).
Lots of things to talk about for this week so let's hop right in.

* TOC
{:toc}

# Change List

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Aivqvz2u7js" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Here is the list of changes added to the project since last week:
* *[v0.0.18](https://github.com/nicholas-maltbie/FallingParkour/pull/21)* - Fixed jittery fan movement.
* *[v0.0.19](https://github.com/nicholas-maltbie/FallingParkour/pull/22)* - Adjusted settings to have players move with
  ground much more smoothly.
* *[v0.0.20](https://github.com/nicholas-maltbie/FallingParkour/pull/24)* - Added a basic game mode for Hex-A-Gone.
* *[v0.0.21](https://github.com/nicholas-maltbie/FallingParkour/pull/25)* - Added a character select screen (featuring
  [Sam's](https://github.com/swiimii) help to code this one). 
* *[v0.0.22](https://github.com/nicholas-maltbie/FallingParkour/pull/26)* - Added a basic menu to select between levels.
* *[v0.0.23](https://github.com/nicholas-maltbie/FallingParkour/pull/27)* - Fixed a few broken features, settings, and
  variables in the game. 

# Feature Highlight - Hex-A-Gone

![Layered maps of hexagon grids for the new game mode, Hex-A-Gone]({{ site.baseurl }}/assets/post-preview/hexagons-update-preview.png)

The feature highlight this week is the new level, Hex-A-Gone. This level is inspired from Fall Guys: Ultimate Knockout
[Hex-A-Gone](https://fallguys.com/rounds/hex-a-gone) round. The map is split up into layers of hexagons which will 
disappear when a player steps on them. When you fall through the final layer, you're out of the round. The last player
standing wins!

This also encouraged me to add a feature for selecting different levels within the game. That way, players can select
from the previously-developed level (Big-Fans) and the new level (Hex-A-Gon). Hopefully I'll be able to add more fun
maps over the next few weeks.

# Future Post - Hex-a-Gons are the Best-a-Gons

![Animation of hexagons being placed radially around a central point]({{ site.baseurl }}/assets/images/hexagon-update\hexagons-anim.gif)

Making the code to create a grid of hexagons for the Hex-A-Gone game was very interesting and I've noticed some interest
in the tile maps from posts on Reddit this week. Since there is some interest,I'll be cleaning up this code and making
a sample project similar to the [Recolor Shader]({{ site.baseurl }}{% post_url 2021-08-20-Recolor-Shader %})
post from last week. Will be working on a fun short video and update post for the future for the tile map code!

# Future Plans

Crossed quite a few things off the list of things to do. These are a few of the times item's we've achieved since last
week.
* ~~Character select screen in main menu~~
* ~~Level select screen for host~~
  * ~~Also, more level besides just big fans~~

Not sure which tasks will be prioritized right away, but these are the current plans for the game:
* End a round once all players have finished (instead of waiting for timeout)
* Score screen to show player scores at the end of round
* Improvement to character controller
  * Knocking the character prone/rag-doll
  * Slippery ground to slide across
  * Bouncy surfaces and objects to jump off
  * Always more debugging...

Can't wait to get started on those next features.

Have a great week

\- _Nick Maltbie_
