---
layout: post
comments: true
title: Development Updates, Our Pausing Solution, & More
thumbnail: https://i.imgur.com/h4HPuI5.jpg
author: Swan
---

Phew! This past week has been super hectic and very productive for Quaver development! Last week we ran a [poll on Twitter](https://twitter.com/QuaverGame/status/1040289230151405569) and opened up the floor for everyone to give their thoughts on how we should handle pausing, and we were met with extremely surprising results. For this week's dev blog, we're going to dive deeper into these results and discuss the solution we've come up with. Furthermore, we're also going to **showcase some development updates in regards to getting Quaver ready for testing!**

# Pausing - Your Feedback & Our Solution!

<p align="center">
  <img src="https://i.imgur.com/R7dL6Ho.png">
</p>

If you're new around here, last week we asked the community for input as to how we should handle pausing during gameplay in terms of its mechanics and how it would apply to submitting ranked scores. **Shockingly, it was very split down the middle between players who believed pausing shouldn't be allowed during gameplay and others who believe it should.**

### Reiterating The Issue

If you're lost about the whole pausing thing, don't worry! We'll explain everything briefly here.

**Note: The following content on pausing is only applicable to ranked leaderboard scores. You will NOT be able to pause in our competitive, elo-based ranking system OR any other multiplayer setting where you are playing against others in real-time.**

**If you're unaware of both of our ranking systems, [check out our first blog post where we discuss it more](https://blog.quavergame.com/Quaver-the-ultimate-community-driven-and-competitive-rhythm-game-explained/).**

To give a quick summary, rhythm gaming is an activity that **drains a ton of stamina.** This means that the longer you play, the more difficult it is to keep the same level of endurance that you've initially had at the beginning of the map. Pausing is an issue in these types of games because it effectively allows the player to regain stamina whenever they choose - ultimately **making gameplay easier than what it was intended to be.**

To reiterate, our goal with Quaver is to power rhythm gaming to the next level by providing **a deeper competitive experience.** Although pausing may seem like a small subject to newcomers, it's **actually a more powerful issue below the surface.** Because of this, we needed a way to allow causal players to pause, but if they choose to do so, it **comes with a price.**

This is why the feedback you've given us was **extremely** useful in drafting the solution we're planning to go with, and we personally believe it's a good one.

If you want to read more about pausing and the issues behind it in depth, [check out the previous week's blog post!](https://blog.quavergame.com/to-pause-or-not-to-pause-you-decide/)

### Reviewing Your Feedback

As you can see in the above image, the results for the poll are **extremely close** - showing that almost half of participants believed pausing should be ruled out completely, another 44% believed that pausing should exist but with a penalty, and a small percentage providing other possible solutions. 

**Doing this larger scale poll allowed us to see that we needed a better solution than what we initially proposed.**

On the first day the poll went live, A community member by the name of *DDMythical* **[wrote up an insightful post on why he believes that pausing is not suitable for Quaver](https://docs.google.com/document/d/12i6gkz4pL0oFTHzFBC5NyyIKye_mgFM-MXVrDifKj4I/edit).** They also address the possible solutions that both we and other community members have brought up and goes into depth why they aren't feasible. Lastly, DD also provides a solution as to we should handle it. It's a very good post, and it is suggested to give it a read **before** taking a look at our solution.

### Our Solution - Holding To Pause

To reiterate once more, Quaver needed a solution where pausing isn't allowed in our ranked setting, but still allows easy access for casual players to do so at will. At first, having an *"Unranked Pause Modifier"* seemed very viable, but after your feedback, we realized that we needed something a bit more.

This is how we've come up with our solution - **Holding To Pause.**

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/DMEsznaZvTA" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

 
 
Here's how it works:

During gameplay, you will still be allowed to pause. **However, doing so will invalidate your score and prevent it from being submitted. It will also mark your score and replay as having paused throughout gameplay.** Once paused, you will also be met with a notification letting you know that your score is now invalid.

To prevent accidental pause key presses, **players are required to hold down the pause key for at least a half a second.** Holding down the key for this long is a good enough length for the game to know that players are consciously wanting to pause and invalidate their score. It's also a decent amount of time to pause throughout breaks in the song if you need a breather.

This is a more viable solution than our initially proposed *"Unranked Pause Modifier"* because players are able to **pause at any point during gameplay and do not have to worry about activating any modifier.** This also achieves the same effect by invalidating scores where players have paused throughout gameplay.

# Development Updates - A Sneak Peek

<p align="center">
  <img src="https://i.imgur.com/Fovy2z3.jpg">
</p>

As far as development goes, I've been working very hard on getting Quaver online. This means developing user authentication, dealing with databases, and implementing a fully featured chat system. Fun!

### Authentication, Username Creation, & Server Login!

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/BAad6Kf6yL4" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

  
The first step in the process was **authentication & server login.** When users log into the game server for the first time, they're met with a screen that **asks them to choose a unique username.** This is **directly connected to your Steam ID, so whenever you log into the game, you'll have the same username along with all of your existing stats.** No extra passwords to remember! Quick and easy.

### In-game Chat!

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/zD4_MO41opY" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

 
The second thing that's being worked on currently is the **in-game chat.** Currently it's setup in a way that feels like home. We're going for a more Discord-y/IRC feel to the in-game chat. **That means public chat channels, and private chats!** The overall design still has to be polished, but the concept is still there.

I'm also exploring the task of creating **private group chats in-game,** so if you'd like to invite a couple of your friends for a private chat, you'll be able to do so!

**Emojis are also on the list** 😎

# Conclusion

As always, if you've made it this far, thanks for reading! Things are moving along quite nicely for Quaver, and I'm happy with the amount of progress we're making. We're one step closer to getting ready for public testing, but there's still a lot that needs to be done before then. Thank you to everyone who participated in last week's poll, as it definitely was a huge help! Until next time!
