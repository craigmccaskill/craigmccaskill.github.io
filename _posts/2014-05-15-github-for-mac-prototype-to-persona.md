---
layout : post
title : GitHub for Mac - Prototype to Persona
author: Craig McCaskill
category : 
---
#### Persona to Prototype - see problem, fix problem

## Background

Building on the work I did previously on my [Usability study on GitHub for Mac]({% post_url 2014-05-05-github-for-mac-usability-study %}), I decided to address the most common problem users were finding with the product. Turns out that usability studies are actually pretty useful!

I also think this is an important problem to address because any time one of your users is using your app for the first time, there’s a good chance it’ll also be the last if they encounter any major issues. With this in mind, I wanted to map out a solution to the first task any user opening GitHub for Mac would want to do: Add a repository.

<!-- more -->

## The idea

From my usability study, it was clear that users expected to be able to add a repository via the SSH clone URL found on the main page of any GitHub.com project page. Instead, the only way to add an existing GitHub repository is to click on the Clone in Desktop button. I propose to augment this existing workflow and also add the ability for users to clone repositories from within the app to give the best chance of a compelling first run experience for a new user of the app.
![clone in desktop image](http://imgur.com/dHIBddfs.jpg)


## Now, lets get to it..
### Gettin’ there - Persona

Before getting to fixing any problems, it helps to actually understand who you’re solving the problem for. If your neighbour is having difficulty setting up their DVR to record the latest episode of Jeopardy!, it might be enough simply to make a few changes to the copy used. The same problem for your grandmother however, mind also require an increase in the font size of the interface and fewer steps throughout the entire flow. Understanding your user is one of the core concepts behind user experience design, so it makes sense to first take a step back and cement just who your user actually is.
![persona image](http://imgur.com/dHIBZdfs.jpg)

Task flow and design stories
Figuring out exactly what you’re going to design to solve a problem is actually a fairly involved process. It helps to start out at a high level with some design stories (what your app or feature needs to be able to do) and start working through what that might look like in a task flow. What ends up happening is as you start going through a task flow you’ll inevitably notice something crucially important you missed and you can go back and re-evaluate based on your design stories, adding and ticking off stories until you get to a point where you have feature-complete list of what your app will do and a start to finish map of how a user would actually go about doing it. 

This iterative process is a great tool for weeding out odd edge cases and shipping a more complete product *before* the support emails start flooding in. 
Design stories

* Copy a remote project
* Import a local project
* Create a new local project
* Change default location
* Create a new local project
* Sync new and existing projects with GitHub
* Create new private repositories
* Connect GitHub account
* Copy all existing GitHub projects
* Copy some existing GitHub projects

##Task flow
![persona image](http://imgur.com/afDJsdtg.jpg)

#Wireframes
Finally, having figured out who this is for, what it’s supposed to be able to do, how it’s actually going to do it, we can start what most people assume is the typical starting point for designing a feature like this &emdash; wireframing. The important part here is to try to keep things as low fidelity as possible and just *keep throwing out as many different ideas as possible. 

I like to start out on paper and just quickly sketch out a 5-6 different ideas. This really gets you thinking about the problem and possible solutions rather than just trying to put a [square peg into a round hole](http://en.wikipedia.org/wiki/Square_peg_in_a_round_hole). Once I settled on an idea I liked, I fleshed it out further on paper before moving into a digital wireframing tool. 

Here’s the final set of wireframes, with annotations.

https://www.lucidchart.com/documents/view/233ef7f5-4814-459e-af0a-7ffdd24e5e80

Prototype
The final goal of any design process like this should be a completed piece that’s fully functional and shipped off to your users for them to enjoy. 

This is not the goal of a prototype. 

A prototype is a communication tool, intended to be a complete manifestation of your intended feature. It is not something awaiting final approval before being whisked off to production. It’s a final sanity check that all the work you’ve done up to this point makes sense. A prototype lets you run usability tests and make any last minute changes or updates *before* you find out, in production, that you don’t handle a specific use case or you missed a crucial interaction.

In some cases, especially when working with an existing app or using a framework, you can ‘skip’ the prototype stage and implement immediately. If this is the case, great, you’ve saved yourself some work. No, you still can’t ship it off to users directly, it’s still a ‘prototype’ and needs to be properly vetted and put in through the fire in a usability study before you let the world at large get their hands on it.

Watch this space, I'm currently working on bringing this to life!
