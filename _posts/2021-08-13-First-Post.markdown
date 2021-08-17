---
layout: post
title:  "Hello World"
date: 2021-08-13 12:00:00 0000
modified_date: 2021-08-16 22:48:00 0000
categories: update
author: "Nick Maltbie"
comments: true
---

Hello world! This is the initial post for the Falling Parkour game that I have been developing with my friends. The game is open source and I'll be posting weekly progress updates here. You can find the current project [here](https://github.com/nicholas-maltbie/FallingParkour).

* TOC
{:toc}

# About the Game

This project is an attempt to re-create the game [Fall Guys](https://fallguys.com/) on a much smaller scale to learn more about multiplayer game development for fun. This blog will have weekly updates as well as informational posts. I may post some of the project updates on my personal blog [nickmaltbie.com](https://nickmaltbie.com) as well, but I’ll include links when appropriate to this project as well. 

I have no expectation that this game will ever be comparable in size to Fall Guys; this is just a fun hobby project. We will probably try to develop it into a small party game (maybe even with a local split screen multiplayer option) to play something more similar to Ultimate Chicken Horse, Screen Cheat, or Tricky Towers. In these games, the rounds are typically shorter and more fun with a group of friends. Maybe include other modes such as timed speed runs for specific maps, a battle royal mode with elimination, local tournaments, etc. The sky is the limit, and I can't wait to see how this project develops.

The current progress of the project includes the following features:
* Multiplayer online gaming
* Pre-game lobby that players can join or leave
* Support for joining a session mid game
* Multiple character cosmetics to select from
* Adjustable settings from main menu and in game

Right now, the game is at a pre-alpha phase of development. This means that it is just experimental ideas and laying out the framework for how the game will be structured in the future. Here is a video showing the current project progress:

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/uh7MN0BLsrk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

> This is Falling Parkour v0.0.13 from August 9th, 2021. you can find the version on GitHub at [v0.0.13](https://github.com/nicholas-maltbie/FallingParkour/commit/c4344c2e1008513a2ae14e1a2a2e443f9f7546c1). The project on GitHub has detailed instructions on how to run and build the project. But if you just want the executable (.exe) file to try for yourself, you can download the windows build as a [zip file](https://drive.google.com/file/d/1oUxA0GNkHyyOcjZ0qMwy3pFm2hGn1dhD/view?usp=sharing).

The project doesn't have too much to work with right now and has a long way to go before it can be considered in the "alpha phase" of development. The next planned features for the project include:
* Spectator camera for when you finish a level (or if you join in the middle of a round)
* Automatic round switching when all players have finished a level
* Loading in more maps from a pool of selected maps (and more maps/hazards)
* Character selection screen in a profile menu
* Score screen for the end of the round

If you have other ideas or suggestions for features you would like to see, feel free to leave a comment or suggestion (or even mess around with the code yourself).

I’ve been working on this project for about a year and a half with friends learning how to use various technical tools. There are multiple other projects that I made leading up to the current [Falling Parkour](https://github.com/nicholas-maltbie/FallingParkour) I'm working on now. Below is a video where I talk about making a game with the Data Oriented Technology Stack (DOTS). I'm still using many of the same ideas and concepts form that project in Falling Parkour. 

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/N4uKXMWs4aE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

> _Since I made the PropHunt DOTS project as part of a school project, I ended up making a video talking about how the code works. Much of this code design is still used in the current version of the project. I’d love to write an update about how character movement works, how client authoritative movement allows for playing a game with minimal lag, and how they are implemented. I will make more YouTube videos discussing these topics in greater depth as I continue development._

# About Nick

I started learning about Unity and 3-D modeling back in my freshman year of college. My first project was called Treachery (based off the tabletop board game Betrayal at House on the Hill) which used an old networking framework Unity (UNet if anyone remembers it). This project hasn’t been worked on for a while, but it has a repository [https://github.com/nicholas-maltbie/Treachery](https://github.com/nicholas-maltbie/Treachery) and an old blog post I wrote about here: [Treachery Project Blog Post](https://nickmaltbie.com/honors/2017/07/28/Treachery.html). I kept up a development log while developing the PropHunt DOTS project before had to switch to a new project [PropHunt Dev Log](https://nickmaltbie.com/PropHuntDevLog/). I wish that I had kept up that old blog; it’s still fun to read through some of those old posts, but time can't afford to be allocated to every project I would like to do. Some sacrifices have to be made.

![Picture of the main room from the treachery project](https://nickmaltbie.com/assets/projects/Treachery/treachery-2.png)

> _This picture is from the [Treachery Project Blog Post](https://nickmaltbie.com/honors/2017/07/28/Treachery.html). I'm very happy with how this project turned out and I learned a lot about 3-D modeling. I actually remade the chandelier asset in blender recently and love continuing to make 3-D models and textures. I used to paint and make clay sculptures when I was younger so I guess this transition to 3D would only be natural_.

<div class="container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Ur3sEam7JCs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
</div>

> _Fun fact: I originally developed a previous project that I also, somewhat confusingly, called Treachery (a different version than the project discussed earlier) back in 2016. I attempted to re-create my favorite board game, [Betrayal at House on the Hill](https://boardgamegeek.com/boardgame/10547/betrayal-house-hill). The video above is me showing a short video of how the project works and walking through a sample multiplayer game. This was my first time developing a 3-D multiplayer game and the idea has always been somethign I've liked to tinker around with on my own time. I don't have a link to the original source code, but if I find it, I will make a short video or post discussing that project and all the interesting stuff I added._ 

By trade, I'm a software engineer. I recently graduated and relocated as part of my job. I won't have as much time to work on my hobby projects (including Falling Parkour) as I had when I was a student. I still hope to keep adding new features to this project, and hopefully I will be able to draft the help of a few friends along the way. Between all the hobby projects I've made over the past years, I've switched between using many different software tools depending on my technical proficiency and the project requirements. In the future, I might make a post discussing the various tools I have used and how they work in grater detail.

# Progress Update for August 15th

Over the next few months, I intend to continue development for this project and post regular updates on this development log. Since I won't be able to add new features, I might just post about how development is going and add a few fun screenshots and features. I'm using GitHub to manage my code and the most recent changes I added were earlier this week:
* [v0.0.13](https://github.com/nicholas-maltbie/FallingParkour/pull/15) - Player Jump Improvements.
* [v0.0.12](https://github.com/nicholas-maltbie/FallingParkour/pull/14) - Fixed rotating fans bug.
* [v0.0.11](https://github.com/nicholas-maltbie/FallingParkour/pull/13) - Recolored fans bug.
* [v0.0.10](https://github.com/nicholas-maltbie/FallingParkour/pull/12) - Added version number to main menu and builds.
* [v0.0.9](https://github.com/nicholas-maltbie/FallingParkour/pull/11) - Removed player sprint.

> Each of these patch versions is numbed as `[major].[minor].[patch]`. So Version `0.0.1` would be major version 0, minor version 0, patch number 1. Each increment in the patch number represents changes to the project. The links in the list above have more information about the changes made to the code. 

## Feature Highlight: Colorable Shaders

My favorite update from this list is the Recolored fans (v0.0.11) because it allowed me to create a shader graph. What's a shader graph you ask?... wait, you didn't ask anything... well, let me explain anyway. A [Shader Graph](https://unity.com/shader-graph) in Unity is a way of telling the game how something should look in the environment. I can describe more how these work in a future post if people are interested. The shader graph that I wrote as part of [v0.0.11](https://github.com/nicholas-maltbie/FallingParkour/pull/13) recoloring a grey scale image. All black pixels are converted to one color while all white pixels are converted to another, grey pixes are blended between them. Then, as an added bonus, a third pattern image can be drawn on top of the background image. Some images of this shader are shown below:

![Sample of the shader being applied to re-color the texture map applied to a cube and then draw an arrow with a gradient on top of it. This is shown within the unity editor and the cube has a yellow border with a orange rounded rectangle drawn within it and a blue arrow drawn on top of it. The right side contains a panel which shows how the textures are recolored from grey scale images and drawn on top of the cube's material.]({{ site.baseurl }}/assets/images/helloworld/recoloring-a-cube.png)
> _This is a sample of how the cube can be textured and colored using grey scale images with a colored pattern drawn on top of it._

![This view represents the shader graph view within unity and how each individual step is applied to the material to re-color a set of images and layer them together.]({{ site.baseurl }}/assets/images/helloworld/shader-graph-sample-picture.png)
> _This is a sample of how the shader graph is applied step-by-step to a set of images. I'd be happy to dive further into how shader graphs work and how any shaders I have created for this project are used to create an immersive experience._

# Concluding Remarks

This post has discussed a lot of my previous projects and future goals. Lots of future ideas and concepts to work with. I'm working with my friend Jorden who who has been proofing and editing these posts. He is working on his own personal blog about fantasy writing - I suggest you check it out if that's something you're interested in [https://dennyjk.wordpress.com/blog/](https://dennyjk.wordpress.com/blog/). You can also read his most recent (recent relative to when this post comes out) post about [Geography Worldbuilding: Eriath](https://dennyjk.wordpress.com/2021/08/14/geography-worldbuilding-eriath/). I hope to continue making weekly posts and regular updates on YouTube, Twitter, and related social media. I hope you have enjoyed this short (_that's a lie, this post is pretty long_) post about the project and future plans for this blog. 

Have a great week

\- _Nick Maltbie_
