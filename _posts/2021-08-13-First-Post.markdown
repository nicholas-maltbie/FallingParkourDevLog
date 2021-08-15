---
layout: post
title:  "Hello World"
date: 2021-08-13 12:00:00 0000
modified_date: 2021-08-14 21:27:00 0000
categories: update
author: "Nick Maltbie"
comments: true
---

Hello world, this is the initial post for the Falling Parkour game that I and my friends have been developing. 

* TOC
{:toc}

# About the Game

This project is an attempt to re-create the game [Fall Guys](https://fallguys.com/) on a much smaller scale to learn more about multiplayer game development for fun. This blog will have weekly updates as well as informational posts. I may post some of the project updates on my personal blog [nickmaltbie.com](https://nickmaltbie.com) as well, but I’ll include links when appropriate to this project as well. 

I have no expectation that this game will ever be comparable in size to Fall Guys; this is just a fun hobby project. We will probably try to develop it into a small party game (maybe even with a local split screen multiplayer option) to play something more similar to Ultimate Chicken horse, Screen Cheat, or Tricky Tower. In these games, the rounds are typically short and more fun with a group of friends. Maybe include other modes such as timed speed runs for specific maps, a battle royal mode with elimination, local tournaments, etc. The sky is the limit, and I can't wait to see how this project develops.

The current progress of the project includes the following features:
* Multiplayer online game
* Ability to load into a game both in a pre-game lobby and during game play
* Allowing for multiple character avatars
* Settings configurations for controls, resolution, etc...

Right now, the game is at a pre-alpha phase of development. This means that it is just experimental ideas and laying out the framework for how the game will be structured in the future. Here is a video showing the current project progress:

<iframe width="560" height="315" src="https://www.youtube.com/embed/uh7MN0BLsrk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> This is version v0.0.13 from August 9th, 2021. you can find the version on GitHub as commit [c4344c2e1](https://github.com/nicholas-maltbie/FallingParkour/commit/c4344c2e1008513a2ae14e1a2a2e443f9f7546c1). The project on GitHub has detailed instructions on how to run and build the project. But if you just want the executable, you can download the windows build as a zip file (be aware when downloading random zip or exe files from online, this not a virus but always be careful): [https://drive.google.com/file/d/1oUxA0GNkHyyOcjZ0qMwy3pFm2hGn1dhD/view?usp=sharing](https://drive.google.com/file/d/1oUxA0GNkHyyOcjZ0qMwy3pFm2hGn1dhD/view?usp=sharing)

The project isn't too much right now and has a long way to go before it can be considered ot be in the "alpha phase" of development. The next planned features for the project include:
* Spectator camera for when you finish a level (or if you join mid-round)
* Automatic round switching when all players have finished a level
* Loading in more maps from a pool of selected maps (and more maps/hazards)
* Character selection screen within the settings menu
* Score screen for the end of the round

If you have other ideas or suggestions for features you would like to see, feel free to leave a comment or suggestion (or even mess around with the code yourself).

Believe it or now, I’ve been working on this project for about a year and a half on a small scale with friends learning how Unity’s [Data Oriented Technology Stack (DOTS)](https://unity.com/dots) works. There are multiple other project repositories that were transformed into the current [Falling Parkour](https://github.com/nicholas-maltbie/FallingParkour) game you see now. 
* Original DOTS project making PropHunt - [PropHunt DOTS Repo](https://github.com/nicholas-maltbie/PropHunt)
* Making PropHunt using [Mirror Networking](https://mirror-networking.com/) instead of DOTS - [PropHunt Mirror Repo](https://github.com/nicholas-maltbie/PropHunt-Mirror)

<iframe width="560" height="315" src="https://www.youtube.com/embed/N4uKXMWs4aE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> _Since I made the PropHunt DOTS project as part of a school project, I ended up making a video talking about how the code works. Much of this code design is still used in the current version of the project. I’d love to write an update about how character movement works, how client authoritative movement allows for playing a game with minimal lag, and how they are implemented. I will make more YouTube videos as I continue development._

# About Nick

I started learning about Unity and 3-D modeling back in my freshman year of college. My first project was called Treachery (based off the tabletop board game Betrayal at House on the Hill) which used the old [UNet framework](https://docs.unity3d.com/Manual/UNet.html) from Unity. This project hasn’t been worked on for a while, but it has a repository [https://github.com/nicholas-maltbie/Treachery](https://github.com/nicholas-maltbie/Treachery) and an old blog post I wrote about here: [Treachery Project Blog Post](https://nickmaltbie.com/honors/2017/07/28/Treachery.html). I kept up a development log while developing the PropHunt DOTS project before I switched to using mirror networking [PropHunt Dev Log](https://nickmaltbie.com/PropHuntDevLog/). I wish that I had kept up that old blog; it’s still fun to read through some of those old posts, but time can't afford to be allocated to every project I would like to do. Some sacrifices have to be made.

![Picture of the main room from the treachery project](https://nickmaltbie.com/assets/projects/Treachery/treachery-2.png)

> _This picture is from the Treachery [Treachery Project Blog Post](https://nickmaltbie.com/honors/2017/07/28/Treachery.html). I'm very happy with how this project turned out and I learned a lot about 3D modeling. I actually remade the chandelier asset in blender recently and love making 3D models and textures, I used to paint and make clay sculptures when I was younger so I guess this transition to 3D would only be natural_. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ur3sEam7JCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> _Fun fact: I originally developed another project called Treachery back in 2016, I attempted to re-create my favorite board game [Betrayal at House on the Hill](https://boardgamegeek.com/boardgame/10547/betrayal-house-hill). The video above is me showing a short video of how the project works and walking through a sample multiplayer game. This was my first time developing a 3D multiplayer game and the idea has always been around as a hobby of interest for me. I don't have a link to the original source code but if I find it soon, I could always make a short video or post discussing that project and all the interesting stuff I added._ 

By trade, I'm a software engineer and have recently graduated and moved as part of my job. I won't have as much time to work on the project as I did over the past year when I was a student. I still hope to keep adding small new features to this project and hopefully I will be able to draft the help of a few friends along the way. One of the major resources the PropHunt project switched from DOTS to Mirror is because the [Entity Component System (ECS)](https://docs.unity3d.com/Packages/com.unity.entities@0.17/manual/index.html) in DOTS was difficult to understand for new programmers and it was easier to encourage them to work on the project without having to understand the complex framework. I might even switch to the new [Unity Multiplayer Networking](https://docs-multiplayer.unity3d.com/) after some further development with DOTS (they are missing a few key features that are promised to come soon).

# Progress Update

Over the next few months, I intend to continue some level of development for this project and post regular updates on this development log. Since I won't be able to add new features, I might just post about how development is going and add a few fun screenshots and features. I'm using GitHub to manage my code and the most recent changes I added were earlier this week:
* [PR #15](https://github.com/nicholas-maltbie/FallingParkour/pull/15) - Player Jump Improvements.
* [PR #14](https://github.com/nicholas-maltbie/FallingParkour/pull/14) - Fixing rotating fans bug.
* [PR #13](https://github.com/nicholas-maltbie/FallingParkour/pull/13) - Recolor fans bug.
* [PR #12](https://github.com/nicholas-maltbie/FallingParkour/pull/12) - Added version number to main menu and builds.
* [PR #11](https://github.com/nicholas-maltbie/FallingParkour/pull/11) - Remove player sprint.
> PR stands for [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request), it is a concept in GitHub where you can add a set of changes to a project all at once. This helps allow for developers to work on different features at the same time, review them, and merge them together at a later point without having to worry about getting in each other's way. This is part of the broader idea of source control for managing software projects. Although, if I explain much more here it would have to be a post of its own, which I would be happy to talk more about in a future post. I made a short explanation on how to use Git for a school project, you can read it [here](https://docs.google.com/document/d/14opTjyyGmNuTWLOhBLnYK4CHvEXVYm0gRKBxeQvBVGA/edit?usp=sharing) if you're interested in learning more. 

## Recent Feature: Colorable Shaders

My favorite out of this list is the Recolor fans bug because it allowed me to create a shader graph. What's a shader graph you ask... what you didn't ask anything... well let me explain anyway. A [Shader Graph](https://unity.com/shader-graph) in unity is a way of telling the render pipeline how something should look on the screen. The concept of rendering, shading, lighting, and materials are all very complex and differ depending on what 3D environment engine you are using and how they have defined their pipeline (_future post idea if people are interested_). The shader graph that I wrote as part of [PR #13](https://github.com/nicholas-maltbie/FallingParkour/pull/13) allows for coloring a gray-scale _background_ image to be two different colors and mix evenly between them. All black pixels are converted to one color while all white pixels are converted to another. Then, as an added bonus, a third _pattern_ image can be drawn on top of the _background_ image. Some images of this shader are shown below

![Sample of the shader being applied to re-color the texture map applied to a cube and then draw an arrow with a gradient on top of it. This is shown within the unity editor and the cube has a yellow border with a orange rounded rectangle drawn within it and a blue arrow drawn on top of it. The right side contains a panel which shows how the textures are recolored from grey scale images and drawn on top of the cube's material.]({{ site.baseurl }}/assets/images/helloworld/recoloring-a-cube.png)
> _This is a sample of how the cube can be textured and colored using grey scale images with a colored pattern drawn on top of it._

![This view represents the shader graph view within unity and how each individual step is applied to the material to re-color a set of images and layer them together.]({{ site.baseurl }}/assets/images/helloworld/shader-graph-sample-picture.png)
> _This is a sample of how the shader graph is applied step by step to a set of images. I'd be happy to dive further into how shader graphs work and how any shaders that I have created for this project are used to create an immersive experience._

# Concluding Remarks

This post has discussed a lot of my previous projects and future goals. Lots of future ideas and concepts to work with. I'm working with my friend Jorden who is working on his own personal blog about writing - I suggest you check it out if that's something you're interested in [https://dennyjk.wordpress.com/blog/](https://dennyjk.wordpress.com/blog/). You can also read his most recent post about [Geography Worldbuilding: Eriath](https://dennyjk.wordpress.com/2021/08/14/geography-worldbuilding-eriath/). I hope to continue making weekly posts and regular updates on YouTube, Twitter, and related social media. I hope you have enjoyed this short (_that's a lie, this post is pretty long_) post about the project and future plans for this blog. 

\- _Nick Maltbie_
