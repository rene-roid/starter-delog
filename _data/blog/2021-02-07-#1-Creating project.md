---
template: BlogPost
path: /#1-Creating project
date: 2021-02-07T23:46:12.174Z
title: Creating the project
thumbnail: /assets/Screenshot-2022-02-07-234109.png
---

# Hello! Welcome to my first Devlog post
This is my first time ever doing a devlog blog, well.. a devlog in general, sorry if my english is kinda wonky and probably none one is going to read this but yeah, I just want to document my progress making this project. I don't have anything planned out, not even the story but I just want to make a rythm rpg game, hope that I can manage to finish this project before quitting ^^'.

## Configuring the project
So here I want to document my process oof making my RPG Rythm game.
Today I created the project, firstly I prepared the hierarchy and the file explorer using TaroDev's unity package, it only creates folders and a template scene to follow.


## Creating the player
After preparing the project I created the player and added a basic movement and camera follow. The movement is controlled with the rigid body and to spicy it a bit i added a sprint! Pretty basic... when the player presses the left shift button the player movement speed increases.

When finishing doing the basic movement I did the camera movement. I could just put the camera as a child of the player, but that would make the movement very static and boring. So I decide it to give it some smoothing, I gave to the camera a target and a smoothing value and just lerped the camera from its position to the target's position with a "delay" that is the smoothing value.

<iframe width="560" height="315" src="https://www.youtube.com/embed/-EqnHSYa9Zg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>