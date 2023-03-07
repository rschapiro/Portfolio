---
title: "Beginning Virtual Reality (VR)"
toc: true
---

Article: https://gamedevacademy.org/how-to-create-a-game-for-the-meta-quest/

Other Links:
https://developer.oculus.com/documentation/unity/
https://developer.oculus.com/documentation/native/android/mobile-intro/
https://developer.oculus.com/quest/
https://developer.oculus.com/documentation/unity/unity-gs-overview/

As you might know by now, my plan is to start developing a virtual reality experience.

When developing a virtual reality experience there are two main factors to consider:

1) Movement
2) Simulator sickness

## Movement in VR
There are two different kinds of movement forms in VR. **Teleportation** and **smooth movement/locomotion**. 

**Teleportation** let's the player point somewhere on the ground and makes him/her able to instantly transport to that point. The player then remains at the designated point until they decide to move to somehwere else. The points where you can teleport to are decided in different ways. You can make specific points that are predeterminded from the developers which makes the movement somewhat limitited. There might be different reasons as to why you would want to do that.

**Smooth movement/locomotion** on the other hand let's the player use the thumb stick on one or both of the controllers instead, and makes them able to smoothly glide over the surface on which they are standing on. There are already companies experimenting with omni-directional treadmills to work together with the smooth movement.

## Simulator Sickness
Sickness from playing VR games is unfortunately a very common issue. When playing or experiencing virtual reality you might see the environment move (e.g. if you are in a car or on a boat), and the fact that you see the environment move around and not feeling it on your body can often create the feeling of motion sickness like you would experience in a car or a plane. This is very important to be aware of as a VR developer since you want people to be able to play and experience what you developed. As a part of alleviating motion sickness during VR, the choice between whether to use teleportation or smooth movement can have a big impact on the likelihood of motion sickness occuring. Teleportation is something that most people can handle and is often included in various games and experiences for VR, however it might not always be and the games and experiences are sometimes designed in a way that you have to be able to handle some moving environments and other things happening. Every man for his taste.

There are some general practices to use when planning and developing for VR:
- If using smooth movement the player should only be moved around by themselves - don't make the player move around due to code or in other ways.
- 