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

##What the heck is this all about?

This book/guide/tutorial is about turning you into a level designer. People also prefer to say "Mapper" because in comparison, Cube2 aka 'Sauerbraten' does not come with as much features as Unreal Developer Kit or Farcry does. But Cube2 has his own idea of fun. What makes Sauerbraten so famous is its way to create worlds. Its Cooperative editmode, where you can create stuff simultaneously is very useful for being creative together. However, level design is not only a hobby, it is an occupation. All information you find in this guide may be applied on other games, I will however always include all essential information about how it's done in Cube2, and what about other games. The focus mainly relies on Cube2:Sauerbraten

This book will cover all the little secrets that you may wonder about: Why do some maps get played, others not? How are some levels fun while others are not fun to play? And eventually, why do some levels get into the next release and some not? Quadropolis is, a good place to start. It is a platform to rate and discuss about maps. If you think you got good material, thats the place to go.

##What are the requirements?

I will not tell you the very basics how to work with Cube2, this guide is for intermediate to expert creators. You should know your entities, how to modify them. How to texturize cubes and the different cubesizes. In the first chapter I will explain a few not so well known details about the cube. You will also need a lot of patience, as you need to get a feeling for whats good and whats not good to play.

#2. Octal Editor 

##Get used to the cube

If you are not familiar with how to handle cube formations and you got no workflow in texturizing

##Different sizes - use them

This belongs partially to chapter three - Layout.
There are different cubesizes which you can use for different tasks.

0
1
2 - Details (Rims, Planks, etc)
3 - Architecture
4 - Layout, Terrain
5 - Layout, Terrain
6

Another few important metrics:

4	playerheight, jumpheight
5	rifle trickjump
6.5	Maximum jump range


	2	Kanten, Geländer und Planken
		Größte ersteigbare Stufengröße
	3	Kanten, Geländer, Balken, Lichter
	4	Kisten, Spielergröße, Terraindetail
		Sprunghöhe, Lichter
	5	Plattformen, Terrain, Segment,
		Sniper-TricksprungHöhe
	6	Stiegensegment, Plattformen
	6.5	Sprungweite

##Know your limits - WTR

#3. Layout

Creating a layout is the first step for beginning a project. You maybe have already an elaborate idea in beforehand about the theme, look or feel of the map. But this is not mandatory, most of the maps need only a tin impulse of an idea to get started.

Some of my casual created maps that had no theme or concept intended became a Deathmatch map. It is very flexible, depending on how the map works without any details or textures. We will go through the creation step by step. We have to know a few little things before we get started.

It is important to NOT start with the details, because those need time. Even worse, you are probably not able to create a consistent style throughout the map. And worst, you tend to lose motivation early because you focus on things that willn not show much of a progress. Keep that in mind. 

##Game mechanics

Every game has its unique set of rules. Consisting out of some constants like gravity, gamespeed, jumpheight and other stuff that creates the concept of the game itself. So unfortunatly you can't just make up your own rules in your world, you got to adapt to the existing gameplay and create layouts that utilize these constants. But there are a lot of other things that influence the gameplay. We have to take care of these entities, Which are weapons, different kinds of gamemodes, jumppads, teleports and a lot more. We will discover later what exactly can make or create a layout.  

Sauerbraten's gameplay is very fast. It is hard to create a Battlefield-similar game experience. Instead, Sauerbraten is known for its need for quick reflexes. Having enough room is important. Talking about every single room or corridor within the level. Of course you can add smaller cable canals or vents, but they are to avoid as they are only for fooling around with other people. (Most of the times)

##Building on the grid

As we covered the different cubesizes and their use before, you may wonder why exactly the size 5 and 6 should be used for layouts.

First of all: it is about mathematics. You can jump a specific height, run at a specific velocity, etc. I have no idea if this was actually on purpose by the creator, but it seems to be that creating gaps with a 5-sized cube is just about the right distance a player can safely jump. Creating other layout elements such as stairs, just go right with this size. This doesn't mean that you have to create every single pathway just a cube wide, having variation is very important. To sum up this chapter: building on the grid saves you time to get a proper layout working without caring too much about the detail. You do not want to throw away a fully detailed and texturized work, so make sure that the layout works before getting on that.

Building on the grid also saves you WTR. You can see them in the lower left corner when editing. This is your how-laggy is-my-map o meter
 
##The building-blocks of layouts 

We just cover the things here, that a layout should only contain before getting into any further detail.

* Stairs/Ramps
* Platforms
* Jumppads
* Dropoffs (One-Way Platform to Platform)
* Teleports
* Obstacles or Stuff to hide behind (Pillars, Crates)
* Terrain
* Others: 
    * Ladders
    * Ropes 

These aspects all define a map, and how it will play. Each factor and element of a map, is attributed to how the end product will function, therefore is an attribute of your map. Putting these elements together and make them play nice needs a bit of creativity. Combining the above will create either a labyrinth or open-area type of map.


##Go with the flow

This is something a guy called Redon teached me, and later on reread in a book called "the hows and whys of level design". When I was not quite sure about my first released map called Arabic I consulted Redon.
He showed me that I should place things in the way where the player would walk or jump next. This sounded a bit unreasonable yet because I thought that I want to challenge the player a bit where he got to hide or place his foots. However, I found out very fast that having the ability to expect how the layout will go, will increase the fun in playing it. Getting stuck in crates or other nonsense will kill the fun in playing your hard work. Flow is what you call when you run and jump without bumping into walls. Make sure to playtest every bit of your layout whenever you add something to it!

##Where to start?

The worst thing how you could get started is to create yourself a border or box. Basically a /newmap will already give you a box-shaped place to edit so what should we do? First: You never know how big a map could possibly get. This is what a lot of beginners are not capable of: expanding when you need to. Has also a bit to do with immersion. If the player is able to see the borders (cut off mountains, boxshaped equally high walls to limit the world) they will notice how "unreal" or not beautiful the map is. But this is only secondary. Most newbies will happily work within the same border without ever emerging to greater layouts whenever it would fit. Again: it is not about how big it is, but think out of the box when you see how things could be done. Most try to work within a boxshaped map and do not dare to break through these walls, even if it would go with the gameflow. It takes some creativity to get started and there are several methods to start with nothing.

Do not have your layout necessarely bound to the theme, if you plan to do, for example an egypt map, think about how fitting would be a clichee like a pyramid, but it wont really be playable if you just place a few pyramids.
Which is why we choose to think about the theme later, even if there are some typical elements for specific themes. It is good to know them but right now they are not helping us to create something playable.
Pyramids would possibly be a nice decoration for the background.


##Purpose

We are going to excavate the "theme" topic just a for a minute. When you create a layout, think about the purpose of it.
Is it a factory? powerplant? graveyard? Think how you can combine them and what kind of elements could fit in there
Think how you can replace some of the above noted building-blocks with theme oriented elements.
A platform could turn into a scaffolding for an industrial theme. A jumppad could be indicated by some particles with an energy source nearby to indicate that its not just a jumppad for the sake of having a jumppad. You get what I mean. Thats something you can keep in mind before we burry the topic for a while again.


#4. Audiovisuals

This chapter covers the aesthetic aspects of your work. This is actually the part where you create a world your player can believe in. That shows that it is not just an artificial world.
This is also the part where we re-excavate the theme topic and dig into it a bit further.

## Architecture

There are some obvious basics to arcitecture.
Only if it is possible to build, there should be reasonable support for ceilings like pillar. Walls that can hold the things that are above. Terrain that can actually hold itself.


    * Architecture
    * Immersion
        * Theme - The look and feel
        * Sound




---
List of smart placed trickjumps w/o rewards.

Healthboost under a level, you got to die to get it.
