---
layout: post
title:  "Update - Spectators!"
date: 2021-08-19 12:00:00 0000
categories: update
author: "Nick Maltbie"
comments: true
---

Hello again everyone, making another short update about the game development this week. Much shorter update than last
week (quite a bit busier at work this week). If you're interested, here is the 
[Hello World Post]({{ site.baseurl }}{% post_url 2021-08-13-First-Post %}) from last week.

* TOC
{:toc}

# Change List

Here is the list of changes added to the project since last week:
* *[v0.0.16](https://github.com/nicholas-maltbie/FallingParkour/pull/18)* - Spectator players, you can now spectate
  other players when you finish the map as well as static points labeled as "Follow-able" objects
* *[v0.0.15](https://github.com/nicholas-maltbie/FallingParkour/pull/17)* - Correcting a small typo in the code.
* *[v0.0.14](https://github.com/nicholas-maltbie/FallingParkour/pull/16)* - Disabled footstep sounds from when a player
  walks around (they were a bit loud and annoying).

# Spectators!

The big change from this week is the inclusion of spectators! A spectator a mode for watching other players move around
the map. As a spectator, you can use the controls "left shift" and "left ctrl" to switch between players that you are
following on the map. Spectators players still have the ability to independently rotate their camera of what or who they
are following. 

A demo video showing the spectators in action can be seen here:

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/<spectator video>" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

Spectators can come into the game in one of a few ways:
1. Joining after the game has started, they become a spectator instead of a regular player
2. Finishing the map changes your player to be a spectator

There can be other ways to turn spectators into the future but this is all that is planned for now.

# Recolor Shader Post

I have written a new post for explaining how the recolor shader works and attached an example project, checkout the
information/tutorial [Recolor Shader Post]({{ site.baseurl }}{% post_url 2021-08-20-Recolor-Shader %}) if you want to
know more about how it works.

Have a great week!

\- _Nick Maltbie_