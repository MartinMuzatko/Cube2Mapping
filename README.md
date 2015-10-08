Text Only Planning of Cube2Mapping Vol2

-----------------------------


1. Introduction
    * What the heck is this all about?
    * What are the requirements?


2. Octal Editor
    * Get used to the cube
    * Different sizes
    * Know your limits - WTR

3. Layout
    * Game mechanics
    * Building on the grid
    * The building blocks of layouts
    * Go with the flow
    * Where to start?
    * Purpose

4. Audiovisuals
    * Architecture
    * Immersion
        * Theme - The look and feel
        * Sound

5. Appendix
    * Know your resources


-----------------------------

#1. Introduction

## What the heck is this all about?

This book/guide/tutorial is dedicated to turning you into a professional level designer and showing you a lot of things to take care about when creating your first levels. This guide is also geared towards professionals to learn something new to extend your horizon.  

This guide is dedicated to simple Level Design games, like Cube2, Minecraft or similar. Creating something awesome with just a few easy-to-grasp tools is the goal here.

What makes these games so popular is its way of creating worlds together. All information you find in this guide may be applied on other games similar to Cube2 or Minecraft. In this guide I mainly focus on Cube2.

This book will cover all the little secrets that you may wonder about: How can a few small additions greatly add to the world. How come that some levels are fun, while others are not fun to play? 

To get an idea how you are doing, feel free to ask Quadropolis.us. It is a nice platform to rate and discuss maps.

## What are the requirements?

I will not tell you the very basics how to work with Cube2, this guide is for intermediate to expert creators. You should know your entities, how to modify them. How to texturize cubes and the different cubesizes. In the first chapter I will explain a few not so well known details about the cube. You will also need a lot of patience, as you need to get a feeling for whats good and whats not good to play.

# 2. Octal Editor 

## Get used to the cube

You should grasp the basic concept of editing before you move on with the advanced stuff. There is not much needed to create an appealing deathmatch map. At least you do not have to be the greatest cube-bender of all times to make a map flowy. Simple blocks for platforms and stairs are often enough for a deathmatch map, to be fun to play.

Having an idea about the different entities in Cube2 is also important.

## Different sizes - use them

This belongs partially to chapter three - Layout.
There are different cubesizes which you can use for different tasks.

- 0
- 1
- 2 - Details (Rims, Planks, etc)
- 3 - Architecture
- 4 - Layout, Terrain
- 5 - Layout, Terrain
- 6

Another few important metrics:

- 4 - playerheight, jumpheight
- 5 - rifle trickjump height
- 6.5 - Maximum jump range

# 3. Layout

Creating a layout is the first step for beginning a project. You maybe have already an elaborate idea in beforehand about the theme, look or feel of the map. But this is not mandatory, most of the maps need only a tin impulse of an idea to get started.

Some of my casual created maps that had no theme or concept intended became a Deathmatch map. It is very flexible, depending on how the map works without any details or textures. We will go through the creation step by step. We have to know a few little things before we get started.

It is important to NOT start with the details, because those need time. Even worse, you are probably not able to create a consistent style throughout the map. And worst, you tend to lose motivation early because you focus on things that willn not show much of a progress. Keep that in mind. 

## Game mechanics

Every game has its unique set of rules. Consisting out of some constants like gravity, gamespeed, jumpheight and other stuff that creates the concept of the game itself. So unfortunatly you can't just make up your own rules in your world, you got to adapt to the existing gameplay and create layouts that utilize these constants. But there are a lot of other things that influence the gameplay. We have to take care of these entities, Which are weapons, different kinds of gamemodes, jumppads, teleports and a lot more. We will discover later what exactly can make or create a layout.  

Sauerbraten's gameplay is very fast. It is hard to create a Battlefield-similar game experience. Instead, Sauerbraten is known for its need for quick reflexes. Having enough room is important. Talking about every single room or corridor within the level. Of course you can add smaller cable canals or vents, but they are to avoid as they are only for fooling around with other people. (Most of the times)

## Building on the grid

As we covered the different cubesizes and their use before, you may wonder why exactly the size 5 and 6 should be used for layouts.

First of all: it is about mathematics. You can jump a specific height, run at a specific velocity, etc. I have no idea if this was actually on purpose by the creator, but it seems to be that creating gaps with a 5-sized cube is just about the right distance a player can safely jump. Creating other layout elements such as stairs, just go right with this size. This doesn't mean that you have to create every single pathway just a cube wide, having variation is very important. To sum up this chapter: building on the grid saves you time to get a proper layout working without caring too much about the detail. You do not want to throw away a fully detailed and texturized work, so make sure that the layout works before getting on that. The same can be applied on webdesign, where you sketch the layout before you get ready for design. Also animations, where you draw a few examples based on the content, before you fully animate and paint the scenes.

Building on the grid also saves you WTR. You can see them in the lower left corner when editing. This is your how-laggy is-my-map o meter
 
## The building-blocks of layouts 

We just cover the things here, that a layout should only contain before getting into any further detail.

 Stairs/Ramps
 Platforms
 Jumppads
 Dropoffs (One-Way higher Platform to lower Platform)
 Teleports
 Obstacles or Stuff to hide behind (Pillars, Crates, be creative)
 Terrain
 Others: 
    - Ladders
    - Ropes 

These aspects all define a map, and how it will play. Each factor and element of a map, is attributed to how the end product will function, therefore is an attribute of your map. Putting these elements together and make them play nice requires a bit of creativity.
Decide which elements should belong to your maps. Think about if you involve terrain in your map or not, and which make sense according to your theme.


## Go with the flow

This is something a guy called Redon (A great contributor to the community) taught me, and later on reread in a book called "the hows and whys of level design". When I was not quite sure about my first released map called Arabic I consulted Redon.
He showed me that I should place things in the way where the player would walk or jump next. This sounded a bit unreasonable yet because I thought that I want to challenge the player a bit where he got to hide or place his foots. However, I found out very fast that having the ability to expect how the layout will go, will increase the fun in playing it. Getting stuck in crates or other nonsense will kill the fun in playing your hard work. Flow is what you call when you run and jump without bumping into walls. Make sure to playtest every bit of your layout whenever you add something to it!

## Where to start?

The worst thing how you could get started is to create yourself a border or box. Basically a /newmap will already give you a box-shaped place to edit so what should we do? First: You never know how big a map could possibly get. This is what a lot of beginners are not capable of: expanding when you need to. Has also a bit to do with immersion. If the player is able to see the borders (cut off mountains, boxshaped equally high walls to limit the world) they will notice how "unreal" or not beautiful the map is. But this is only secondary. Most newbies will happily work within the same border without ever emerging to greater layouts whenever it would fit. Again: it is not about how big it is, but think out of the box when you see how things could be done. Most try to work within a boxshaped map and do not dare to break through these walls, even if it would go with the gameflow. It takes some creativity to get started and there are several methods to start with nothing.

Your layout doesn't need to be necessarely bound to the theme. If you plan to build, for example an egypt map, think about how it would fit in the map. Especially clichees for a specific theme (like pyramids for egypt maps), aren't quiet playable standalone. Which is why we choose to think about the theme later, even if there are some typical elements for specific themes. It is good to know them but right now they are not helping us to create something playable.
Pyramids would possibly be a nice decoration for the background.


## Purpose

We are going to excavate the "theme" topic just a for a minute. When you create a layout, think about the purpose of it.
Is it a factory? powerplant? graveyard? Think how you can combine them and what kind of elements could fit in there
Think how you can replace some of the above noted building-blocks with theme oriented elements.
A platform could turn into a scaffolding for an industrial theme. A jumppad could be indicated by some particles with an energy source nearby to indicate that its not just a jumppad for the sake of having a jumppad. You get what I mean. Thats something you can keep in mind before we burry the topic for a while again.


# 4. Audiovisuals

This chapter covers the aesthetic aspects of your work. This is actually the part where you create a world your player can believe in. That shows that it is not just an artificial world.
This is also the part where we re-excavate the theme topic and dig into it a bit further.

## Architecture

There are some obvious basics to arcitecture.
Only if it is possible to build, there should be reasonable support for ceilings like pillars. Walls that can hold the things that are above. Terrain that can actually hold itself. in this 

## Immersion

Immersion is one of the most important concepts in every leveldesign. If your surroundings are not believed by the player, you do a bad job. This means that most flowing map is still fun to play, but it doesn't look real. After you have chosen the right theme and context, your only goal is to not corrupt the current existing layout with details. Cluttering the layout with details that render previous existing jump or walkpaths unflowing, will result in a mess for the player. So balancing out layout and design is a tough task. Overusing clip and no-clip will not fix a flawed layout.
So here is what you can do to immerse the player into your world:

### let your worldborder vary in height and material
If you have a flat ceiling, add some open spaces inbetween and vary in height. Nobody is getting there anyway. Unless it is the ceiling between the current and the next floor, feel free to add holes where light can come from and to make the skybox appear more often. This applies specially to rather closed maps. If you have a rather small but open DM map, try to add a lot of diversity to the walls, make them half terrain-half metal/brick/whatever so you can add some variation. Additionally you can vary in depth, height and material. Adding a watterfall as long it plays nice with the layout works too.

### Less surface detail on floors.
As long it is subtle enough, so it does not interfere with the flow, you can add details on the floor. Mainly rims and missing tiles and different textures on the floor where it is convenient. Adding holes to the floor with grills over them will make a nice underground detail.  Walls are fine, as long you don't get stuck in them. The ceiling is (if high enough) where you can put all of the details. For the terrain, it is rather the opposite. The floor is as smooth as possible, whereas the higher the wall/cliff, the more bulky you get on the top.

## Terrain

I chose Terrain to be an extra chapter in Audiovisuals, to cover the more advanced techniques to create immersive terrain. Lets point out the possibilities we have:

### What does terrain include?

**Larger components:**
 - Caves/Tunnels
 - Cliffs
 - Hills
 - Slopes
 - Ravine
 - Voids
 
**Smaller components:**
 - Boulders and Rocks
 - Stalagmites
 - Stalactites
 - Pillars

Unfortunately, terrain is rather tough to create. Even if you are a skilled mapper, it takes a few hours to bevel out a whole map. Because of this, most of the mappers decide to keep it simple. Which is why almost every terrain in Cube2 is eroded (flat). There are no pointy rocks or bolders, just flat terrain that nuzzels and wraps around the buildings. Our goal is to create appealing terrain that fits the theme.

### A few examples

**Egyptian/Desertlike/Orient**

Sand can be rather wavy and create hills, but very smooth. If you know places like the petra (see google images), you know that there are places with very rough cliffs and pointy bolders lying around, yet very smooth sand wrapping them at the bottom. Bolders can also stack up to form towers. There are also special forms of structures often associated with desert environments: arches made out of rocks and steep plateaus. Google for Mesa geology to get your inspiration started.

Starred content with that theme: flagstone by Nieb

**Forest/Grassland/Mountains**

The most typical environment. Everyone imagines a sunny day with a nice forest and some wellrounded mountains. You want to try to turn these 0815 maps into something different. river_c is an exceptional example. With less trees, but significant elements like cliffs and there is a lot of change in height. Always use together with a lot of vegetation.

**Snowstorm/Ice**

An appealing theme that requires a bit of detailwork. You have less vegetation here. Try to fit the clichée of winter environment and add spruce trees as example. dead bushes and a few flowers are also allowed, depending on how severe the winter is/was. 

**Beach/Jungle**

Beach environments are commonly combined with a grassland or jungle landscape. Comparable to the desert, a beach can include rocks and boulders combined with slopes. 


### Other Examples

 - Swamp
 - Jungle
 - Taiga
 - Ocean
 - be creative


## Vegetation

Everything thats green or resembles nature in any way goes here. 

Unfortunately, you have to heavil rely on models (like in xenon) if you want to save a lot of vertices.

Unlike trees, simple plants can be created by using cubes.

    * Architecture
    * Immersion
        * Theme - The look and feel
        * Sound




---
List of smart placed trickjumps w/o rewards.

Healthboost under a level, you got to die to get it.
