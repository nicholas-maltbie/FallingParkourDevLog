---
layout: post
title:  "Update - Spectators!"
date: 2021-08-20 00:00:00 0000
modified_date: 2021-08-21 18:21:00 0000
categories: update
author: "Nick Maltbie"
comments: true
---

Hello again everyone, making another short update about the game development this week. Much shorter update than last
week (quite a bit busier at work this week). You can download a copy of the project [v0.0.17 for windows](https://drive.google.com/file/d/1ax2PGef7xrlyaPZgja3UgF7aC2Esqd4A/view?usp=sharing).
If you're interested, here is the [Hello World Post]({{ site.baseurl }}{% post_url 2021-08-13-First-Post %})
from last week introducing the project.

* TOC
{:toc}

# Change List

Here is the list of changes added to the project since last week:
* *[v0.0.17](https://github.com/nicholas-maltbie/FallingParkour/pull/20)* - Fixing bugs in spectator code that was added
  in previous patch.
* *[v0.0.16](https://github.com/nicholas-maltbie/FallingParkour/pull/18)* - Spectator players, you can now spectate
  other players and static points labeled as "Follow-able" objects when you finish the level.
* *[v0.0.15](https://github.com/nicholas-maltbie/FallingParkour/pull/17)* - Correcting a small typo in the code.
* *[v0.0.14](https://github.com/nicholas-maltbie/FallingParkour/pull/16)* - Disabled footstep sounds from when a player
  walks around (they were a bit loud and annoying).

# Feature Highlight - Spectators!

The big change from this week is the inclusion of spectators! A spectator a mode for watching other players move around
the map. As a spectator, you can use the controls "left shift" and "left ctrl" to switch between players that you are
following on the map. Spectator players still can independently rotate their camera around what or who they
are following. 

A demo video showing the spectators in action can be seen here:

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/79Nm3eWgQIg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Spectators can come into the game in one of a few ways:
1. Joining after the game has started, they become a spectator instead of a regular player
2. Finishing the map changes your player to be a spectator

There can be other ways to turn spectators into the future, but this is all that is planned for now.

# Recolor Shader Post

I have written a new post for explaining how the recolor shader works and attached an example project, checkout the
information/tutorial [Recolor Shader Post]({{ site.baseurl }}{% post_url 2021-08-20-Recolor-Shader %}) if you want to
know more about how it works. It has an example project stepping through each part of the shader and explaining how it
works.

<div class="container">
<img src="https://github.com/nicholas-maltbie/Recolor-Shader-Example/blob/main/Examples/imgs/Showcase.png?raw=true"/>
</div>

# Future Plans

The next few features planned (in no particular order) for the project include:
* Auto end a round when all players have finished (instead of waiting for timeout)
* Improvement to character controller
  * Knocking the character prone/rag-doll
  * Slippery ground to slide across
  * Bouncy surfaces and objects to jump off
  * More debugging of jumping and falling mechanics
* Level select screen for host
  * Also, more level besides just big fans
* Score screen to show player scores at the end of round
* Character select screen in main menu

Have a great week!

\- _Nick Maltbie_
