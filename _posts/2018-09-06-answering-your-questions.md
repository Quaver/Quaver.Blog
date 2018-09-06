---
layout: post
comments: true
title: Answering Your Questions about Quaver
thumbnail: https://i.imgur.com/D9s2REX.jpg
author: Swan
---

Thank you all so much for the overwhelming support on last week's reveal/blog post! To be honest, we did not expect it to have as big of a reach as it did! The support and love you're showing us so far has made us even more motivated to provide you with a great game to play.

This week's dev blog is dedicated to answering your questions, and boy there were **a lot** of them. The questions and answers are going to be broken down into their own subsections. 

Keep in mind that Quaver is still in its early stages, and things are subject to change at any point. This is just to give you guys a rough idea of the direction we're headed.

# General Questions

<p align="center">
  <img src="https://i.imgur.com/TTsYsQ0.jpg">
</p>

There have been some general questions about the game regarding its release date, platforms it'll run on, and more. We'll be answering that in this section.

### When is the game coming out?

While we have no set release date, we're looking at having an official alpha release sometime this fall. There will be more details on this at a later date.

### What platforms will the game be released on?

At initial release, we're looking at Windows only. However, the game should be relatively easy to port over to all different platforms (Mac, Linux, iOS, Android). You should be able to run the game on Mac/Linux currently however.

### What will be the price of the game?

Free.

### What platform will the game be on?

Steam.

# Feature-Related Questions

<p align="center">
  <img src="https://c1.sfdcstatic.com/content/dam/blogs/us/thumbnails/8-creative-ways-to-use-instagrams-new-multiple-image-posting-feature/instagram_header.png">
</p>

There's no doubt that the majority of you have had questions about the features of the game and have requested things you'd like to see going forward. Let's get going!

### What key modes are planned for the game?

Quaver currently only supports 4 keys and 7 keys. The reasoning for not adding more initially is because we're splitting the ranking leaderboards between the two modes. If we were to have 10 different key counts, that would mean 10 different leaderboards. However, if the community finds that they want more key counts in the future, we can add this in easily.

### Will we be able to have separate skins for each key mode?

Yep. This is already implemented.

### Will Quaver have an in-game editor?

This is planned. In fact, we're exploring the option of having an in-game editor and a standalone editor. You'll be able to access the editor both in-game and out as a standalone desktop application. This is so that if you're interested in creating maps without having the game open, you'll be able to do so. They'll of course function exactly the same.

### Will I be able to convert skins from other games?

Yes! Our skinning system should be modular enough to use skins from other games. Albeit you'll have to do some file renaming to get it to work, but it should be easy to get the job done.

### How exactly will the elo system work?

Given that this is an extremely big feature, we're planning to have this in its own separate blog post and invite the community for feedback on it. Stay tuned on this. If you'd like a brief overview of how it'll work, you can check out our [previous blog post](https://blog.quavergame.com/Quaver-the-ultimate-community-driven-and-competitive-rhythm-game-explained/).
### Will the game feature storyboards/video?

If this is something the community wants, we wouldn't mind adding it. However it isn't high on our priority list at the moment.

### Will SVs exist in the game?

Definitely. The goal is to allow map creators to eventually be as creative as possible without limitations. 

### How will the difficulty system work?

We're planning to have difficulty ratings be calculated automatically. We're aiming to have a system that uses deep pattern analysis of the given map, and we've already been prototyping a system for 4K which you can see [here](https://docs.google.com/spreadsheets/d/106yXQWfPR5Iw0ol2Q9UVraNqBKCY09DteWFDGJ6w1Ks/edit#gid=1230321224). 7K on the other hand is going to be a bigger challenge. There's still a lot of work to be done in this area, and we're working hard on this. We'll definitely be asking the community for input on this in the future.

### How do you plan to do map/chart rankings?

This is still being discussed internally as to how we want to go about it. We want to create a system that is both easy for quality maps to get recognized for rank and a simple task for the people managing it. We're open to suggestions if you have any.

### Will I be able to play with upscroll?

Yes. This is already implemented.

### Will I be able to spectate other players?

Definitely. This should be implemented pretty soon actually. We also want to implement a system where you can spectate multiple people at once.

### Will you support the BMS file format & what will you do about the scratch key if the game is 7K?

If this is something the community wants, we can add this in. As for the scratch key, we'll be able to support this easily with a game modifier, so ideally you would be able to play both the 7K and 7K + 1 version of the chart.

# Open Source Questions

<p align="center">
  <img src="https://mtutriangle.org/assets/img/posts/Open-Source-Word-Cloud.jpg">
</p>

There have been a **ton** of questions regarding Quaver being open source, so we'd like to answer them in this section.

### Will Quaver be open source? If so, what parts of it?

A good portion of Quaver will be open source. Our game client, our website, and external libraries will all be available under an open source license. Our game server and other netcode related repositories will not be open source however.

### Which open source license will you use?

Different portions of the game will have different licenses. Our external libraries such as our game framework, [Wobble](https://github.com/Quaver/Wobble), will definitely be licensed under MIT. As far as the game client itself, this is still being discussed, as it is one of the most challenging decisions to make.

### When will you go open source?

We're planning to have the game client and its external libraries open sourced by the time for the alpha release. This may come even sooner. There are still internal matters to consider when open sourcing our client such as licensing and game asset protection. We also definitely want to get our Steam page going before open sourcing the game as well. 

### How can I help develop Quaver now?

If you're a C# developer looking to help out now before we open source the game client, we have a ton of issues opened in [Wobble](https://github.com/Quaver/Wobble/issues), the framework portion of our game. Tackling these issues will definitely be a big help.

If you're interested in helping develop our difficulty calculator, we're looking for people to assist with this as well in terms of both theory and maths. 

We're also looking for artists who are great at UI design. If this is something that interests you, feel free to hit us up!.

If you're interested in contributing with the both of these, feel free to join our [Discord Server](https://discord.gg/nJa8VFr) where all of our developers, contributors, and supporters are chatting.

# "Business Model" Questions

<p align="center">
  <img src="https://i.imgur.com/EUztGv3.png">
</p> 

It's no doubt that running Quaver won't be free to do. However with our "business" model, our main goal is to provide a game experience that **everyone** can enjoy whether you pay a cent or not. 

Keep in mind, that all of these are **optional** and will not impact the experience for normal users. 

Here's what we're proposing to do, and these may be subject to change at any time:

### Backer/Supporter System

Given the open source nature of Quaver, we're looking at implementing a backer system where if users are enjoying the game, they can help support us financially for extra perks.

Here's some of the perks we're looking at for this system:

- • **The ability to complete extra in-game challenges for rewards such as unlockable titles and emblems to display on your in-game playercard.**
- • **A badge and color in the in-game chat that shows you're a backer.**
- • **A badge on the website for your user profile that shows you're a backer.**
- • **The ability to change your username once for free every 30 days.**
- • **Access to new in-game features before they're released.**
- • **The ability to create group chats in-game.**
- • **Faster in-game map download speeds.**
- • **The ability to upload more maps at a given time.**
- • **The ability to customize your profile on the website with backgrounds and banners.**
- • **A role in our Discord server that shows you've supported the game.**
- • **Access to an in-game backer-only chat channel.**
- • **Access to a Discord backer-only chat channel.**
- • **Higher vote priority with feature requests.**

We're most likely looking at implementing the backer system in different tiers and depending on which tier you support us with will determine the amount of extra features you receive.

You will also of course be able to gift these to your friends if you're ever so kind. 

### Username Changes

With our backer system, you'll be able to change your username once every 30 days for free. If you decide that isn't for you, but you'd still like to change your in-game username, we'll have an option to do so with this system.

# What about user-created maps and copyright claims for their containing songs? What about Steam?

We're going to be taking this **extremely seriously.**

All user created maps will be uploaded onto our servers while Steam is **only** responsible for providing you with the game client. 

In our terms of service, we'll require and expect users to have had explicit permission from the artists they are creating maps for. If we receive any complaints/notices, they will come to us directly, and we will act with full DMCA compliance by removing said content and discontinuing access for repeat offenders. 

We respect content creators and the hard work they put into their tracks, and the last thing we want is for them to feel that their content has been used unjustly.

This is similar to any other content delivery network such as YouTube, Facebook, and Twitter, and we plan to operate in a similar manner.

We plan to work with a ton of artists in the future which will allow the Quaver community to use and create maps with their tracks freely.

# Final Thoughts

Overall, there's definitely more things in store for Quaver. To reiterate, our goal is to develop the game in such a way that users in the community are openly invited to join in on its development.

Our main priority is to develop a good game first, and we believe that if we do a good job, we'll be supported financially as well.

As stated above, nothing is final and Quaver is still in its early stages, so things are subject to change all the time! This leaves us open to making the game as great as possible with all of your feedback.

If you've read this far, thanks for reading! I enjoy writing these, and I hope you enjoy reading them as well. Let's shoot for the stars!
