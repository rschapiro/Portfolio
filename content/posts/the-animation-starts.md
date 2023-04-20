---
title: "The Animation Starts"
date: 2023-04-20T14:33:34+02:00
draft: false
toc: true
images:
tags:
  - Blender
---

So back again here. So Mondayt and Tuesday I started working on animation in Blender. My goal for this week was to try and make animations in both Blender and Unity to see how each worked, and to compare them to see if one would be easier or more versatile. Since we're working on this project for making a first aid simulation I wanted to make something I could apply to my project. Therefore as the first animation I tried making the chest of the first aid doll move.

I made this work with a simple animation that works with making keyframes for the position of the chest. I'm not gonna show this because I made it on a model I downloaded from the internet. There will be pictures here though, but only from my own model.

## Let's go!
First up I wanted to make the chest move. This turned out to be more difficult than I expected. This was because the approach for making the chest move that I went with, was using the edit mode of Blender. In this way I was able to freely manipulate with the mesh that made up the body of the model, as you can see in the picture below:

{{< image src="/img/blender/animation/without-rigging/chest-in.jpg" alt="chest in animation" >}}

So here I marked an area of the chest and indented it into the torso to make it look like someone was pressing it, a.k.a., as to simulate someone doing cpr. But in this was way I couldn't differentiate between when the chest was in or out, since the keyframe could only be used as if the body would move (the whole torso object would be placed somewhere else) instead of only being shaped in a particular way.

As you can see in this picture it's stille the same shape for the whole keyframe (you can see it that animation doesn't change because of the long yellow line).

{{< image src="/img/blender/animation/without-rigging/same-animation.jpg" alt="same animation" >}}

I made it on the other model (the one I'm not showing) by cutting out the chest, and having that object alone move into the torso for the second keyframe, and back out afterwards. I got to work with the graph editor for this one as well, which was very interesting. A very nice tool I must say. I got stuck in some API call for the project in Unity during the last two days, so hopefully I will be back working on more animation soon.