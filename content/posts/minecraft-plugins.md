+++
title = 'Minecraft Server and Plugin Development'
date = 2024-03-07T09:25:15-08:00
draft = false
tags = ["Minecraft", "Plugins"]
categories = ["Previous Projects"]
weight = 5
+++

**In this blog post I talk about my experience learning to create Minecraft Servers and Plugins.**

---

# Backstory
As a kid I played a lot of video games. I mainly played Minecraft on popular online servers like Mineplex and Hypixel. During these days, I would wake up, hop on a call with my friends, and we would just play games. As I got older, these servers started to fade away and things changed. However my love for those experiences hadn't gone away (probably due to nostalgia). 

Regardless of the reason, this is when I made the decision that I wanted to create my own server. I wanted to see what it was like to be on the other side of the game. This was my entry point into game development.

---------------------

# Server Development

## Setting up a Server
This section isn't a full tutorial on how to set up a server but goes over the general outline and what I used. 

1. **Hosting**

When creating a minecraft server you need a place to host your server. I initially chose to use a provider called [Shockbyte](https://shockbyte.com/) because it was easy to use and fairly cheap for low-end servers. I didn't need anything fancy so this worked fine. 

A couple years later, I switched to another server provider called [Contabo](https://contabo.com/en-us/) which was a cheap service with a more computer resources. The downsides were that it didn't have much of a user interface and it wasn't very secure.

2. **Interacting with Server**

For Shockbyte, there's a website where you can interact with your server. You can start and stop your server and change files around. It made it fairly easy for someone new like me who didn't have much server knowledge at the time. 

When I moved to using Contabo, there was no easy way to interact with the server (which is part of the reason it was a cheaper option) and so I used an application called Filezilla. At the time I didn't fully understand it, but Filezilla allowed me to SSH into the Linux server to be able to interact with the files on that computer.

3. **Adding Plugins**

If you want to make a default Minecraft server then you don't need to do anything more. However, the part that made the servers I played so fun, was the plugins. 

Adding plugins is fairly simple. You first need to be using a server type that supports plugins like spigot. Then you will be able to either download the plentiful amount of plugins online or create your own. I started with downloading online because I had no idea how to make my own but most of the plugins are very configurable.

---------------------

# Servers I Created

## Factions
At first when I was creating a minecraft server I mostly used online plugins and maps. I didn't know much at the time but I knew that I wanted to make something! I convinced one of my friends to help me out and we got to work. Originally, we decided we were going to make a factions server. Looking back it's a little ambitious but we were excited and that's all that mattered. 

My friend who was a factions expert from playing on a server called CosmicPvP helped balance the shop and figure out what we needed. We worked hard on building the spawn, configuring faction plugins, and creating the shop. Despite our efforts at some point or another we stopped working on the project. We might have figured out that it was over ambitious or that we wouldn't be able to get enough players for such a big gamemode. With that we stopped development on the factions server and moved on.

## Kit PvP
Eventually we came back for round two. We learned from our previous ambition and set out to create a much simpler gamemode, KitPvP. This time we had some knowledge to work off of and again we repeated the process of building maps, configuring plugins, and this time we created a discord server. 

Unlike last time, this time we actually released the server online! We posted our server on many websites. Sure we were at the bottom of the lists, but we were still there! 

Somehow a group of people found our server and joined. We were ecstatic and spent some time playing our gamemode with them. It was such a joy to see other people enjoying something we worked on. We had made our own server and created a memorable experience! What a success.

Despite gaining a few players initially it didn't take long for the server to die. We took a little break but I wasn't quite done with creating servers yet. I had bigger more ambitious ideas!

## Skyblock
Next we created a skyblock server (I guess we didn't learn much from creating a factions server). This was my favorite gamemode so I wanted to see what I could do. 

It was at this point as well that I decided it was a good idea to create a staff team. It wouldn't take me long for me to figure out this was a mistake, but young, naive me wanted to expand! 

With this I started looking online for people who wanted to join. After some time I found a couple people who were interested and we all started working on the server despite me having no experience managing other people let alone barely being able to manage myself. Together, we created a discord, configured the gamemode, and more. 

The novel factor of our skyblock gamemode was a place called the 'adventure.' The adventure was an area where players could explore, fight mobs, and loot. It was something I poured a lot of time into creating. I learned how to sculpt a map, create custom mobs, and randomize loot. 

Despite the success of the creation of the skyblock server we never ended up releasing it to the public. I can't remember why but it was most likely due to not being able to finish such an ambitious project and keep the team together. Although this was the end of my time creating servers it lead me down a new path of plugin development.

---------------------

# Plugin Development
When I was creating these servers I conistently wondered how people create the plugins that I used. I was curious but too intimidated to start doing anything. I remember asking my brother to create a plugin for me once since he knew how to create minecraft plugins and I didn't. Eventually after getting tired of begging my brother to work on the project I decided to learn how to do it myself. 

At the time, it was a little overwhelming but I followed an online course on [Udemy](https://www.udemy.com/) called "Develop Minecraft Plugins (Java)" by Stephen King. I loved this course. As a person whose rarely coded prior to following this course, it felt reinvigorating to be able to make changes so easily and see them happen in-game. 

__I would definitely highly recommend modifying existing games if you want to get into game development. Games like Minecraft, Roblox, and now even Fortnite make this easily accessible.__

After learning the basics and going through the majority of the course I got to the most exciting section: minigames. This section was the culmination of all the skills gathered in the course and allowed developers to create the games that people love to play. 

Creating minigames involved many different parts and wasn't as easy as I thought but I created my first minigame of tag. It may sound pretty boring and insignificant but for me at the time this felt truly revolutionary. Knowing that I created something just felt empowering. It gave me a purpose and excitement for the future. I then got to play it with my brother and it was actually quite a bit of fun since I included a custom map for the game and powerups. 

After this I then started working on a way more ambitious project called Intergalactic based on the server called Island Clash. Similar to how the servers went, I took on more than I could chew. During this time I was transitioning into high school and with how busy it was I stopped plugin development for a while.

---------------------

# Where I am Today
Almost six years later from the start of my development process brings me here today. My journey has consisted mostly of failures but also a lot of learning. I hope you've learned something from reading about my journey. 

Ending on a high note, earlier this year I created a custom plugin which I will most likely share in another article. I have big projects in the works, but it's going to take me a while because I have a lot to learn. I hope you enjoyed reading my first ever post because there are a lot more to come. If you have any comments, questions, or suggestions please reach out to me! I'd be more than happy to talk.
