---
layout: post
comments: true
title: October 2018 - Development Update
thumbnail: https://i.imgur.com/V2mJeJK.jpg
author: Swan & Staravia
---

Has it been a month already? Time flies! We've been a bit quiet lately, but don't mistake our silence for no progress. Actually, it's quite the opposite! Over the past month, there have been a **TON** of development updates, and we're excited to share them all with you!

As we start to enter the final stages before our alpha release and open sourcing the Quaver game client, **the main focus at hand is polishing the game and working on our Steam store page.** This means completing tasks such as redesigning our game's UI to give it a fresh look, adding in any missing key features, and fixing any bugs we come across. Once this is complete, we should be good to go to open up the game for players to try and give us feedback on. Let me be clear that our goal is to provide a great first gameplay experience for our players, so your patience is appreciated while we're getting things in order. With that being said, let's get going!

# Quaver Client Updates

<p align="center">
  <img src="https://i.imgur.com/RvQGetO.jpg">
</p>

The bulk of the updates this month lies within the game client - from giving Quaver's main menu a new look, gameplay enhancements, in-game chat improvements, and much more!

### Main Menu Design

As stated before, the main focus at hand is redesigning our game screens and polishing it up to make it pleasing to look at and professional. We're currently working with a graphic designer who is developing these screen designs, so we can understand the direction of how we want the game to look. To give you a sense of what we're going for - it's minimalistic, aesthetically pleasing, and easy to understand for new players.

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/fRfA6TjLs5A" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

--- 

As you can see, the main menu is pretty simple, but featureful. It comes with the following features/design choices:

#### Middle Panels

Allow you to head to different screens in the game.

#### Playercard

Displays your stats for the currently selected game mode (4K or 7K). The playercard design is still fairly rough and will most likely be beefed up in the future.

• **Displays the title "Offline Player," which in the future we want to make unlockable via challenges.**

• **A "?" symbol used as a placeholder for your competitve rank badge.**

• **Overall Performance Rating**

• **Overall Accuracy**

• **Global game mode Rank**

• **Country game mode Rank**

• **Play Count**

• **Total Competitive Wins**

#### Jukebox

Chill out and listen to all your favorite tracks in the main menu with our music player. It also comes with an audio visualizer if you're looking for something pretty to look at!

#### Menu Tips

If you're lost, have no fear! We've got menu tips. Every 10 seconds a new menu tip will display and give you some information about the game.

#### Navigation Bar

With our navigation bar, you can open up different screens/dialogs such as chat. It also comes with the ability to log in and out of the server whenever you choose.

**Hint:** If you've noticed, there isn't any place to enter a username or password. This is because your **Quaver account is linked to your Steam account.** No extra usernames or passwords to remember! Whenever you log into the game server the first time, you'll be prompted to select a unique username.

#### Exit Game Dialog

When pressing ESC in the main menu, it'll come up with a dialog asking you if you'd like to exit the game - Something standard used across the majority of games.

---

Overall, I'm very happy with the way the menu looks for now. As with everything, there's always room for improvements, and we'll definitely be making them overtime when we get more feedback and have more requirements to fulfill. At the moment, we're looking at having a simple and minimalistic design that is quick to implement, so we can get the game out to you all as soon as possible for feedback on what to improve.

Special thanks to both [@saucictb](https://twitter.com/saucictb) and [@leisssw](https://twitter.com/leisssw) for their artwork on the main menu background.

## In-game Chat Improvements & Additions

Another thing I've been working on is improving the overall quality of the in-game chat. This means handling optimizations, design updates, and adding new features.

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/gA6ZTEgKljA" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

---

Visually, the chat is still very much the same as when we showed you the first time. We've changed the color a bit of the interface and also added something handy to the right. Here's what we've done: 

### Online User List

You can now view the list of currently online users on the right-hand side!

#### Filtering Options

There are 4 filtering options for the online user list:

• **All** - Displays all online users.

• **Friends** - Not implemented currently, but it'll display your current online friends.

• **Country** - Displays users that are online in your country

• **Search** - The ability to filter and search for users by username.
          
#### User Client Statuses

Show off to the world what you're doing in-game - whether you're idle in the menus, playing a map, watching a replay, or paused in-game - all other online users will be able to check out what you're up to!

#### User Privilege Groups

You should never have to worry about about wondering if a user is an admin, developer, or moderator on the server. On the online list, it'll display their name and avatar as the same color as their user privilege group.

#### Joining Chat Channels

There's now a dedicated interface for joining and leaving different chat channels.

#### Chat Badge/Avatar Improvements

Chat badges now have a border around them to make them look a bit better than they were before as well as avatars.

#### Chat Message Performance Improvements

This is more of a nitty-gritty development improvement, but chat message containers now have a form of object pooling, so that performance is in tip-top shape no matter the amount of messages the user has backlogged.

---   

There's still a ton of work to do on the chat such as fixing that nasty avatar bug, other graphical errors such as those not-so-great-looking divider lines, and implementing a solid interface for when you click on users in the online list. The overall design for the chat interface is still a work in progress, but it's great to see things finally start coming together in a workable state.

## Gameplay Improvements & Additions

Aside from the above, [@Staravia](https://github.com/staravia) has also started work on improving gameplay performance as well as implementing some new features.

### Slider/Scroll Velcocity

One thing Quaver didn't have previously and does/is being worked on now is SV. If you're unaware, SV or Slider/Scroll Velocity allows the creator of a map to dynamically change the speed at which objects fall down the screen allowing for more creativity when making maps.

Here's a taste:

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/uanWl2LnkOo" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

---

**Track List**:

1. **"Leaf - Lyrith"** *(Mapped by: Vortex-)*
2. **"BEMANI Sound Team (PHQUASE vs DJ TOTTO) - TWO-TORIAL"** *(Mapped by: MAAAAAAAAAAAAAS)*
3. **"SUNKU - Batting Show (Perfect Version)"** *(Mapped by: Daiyki)*
4. **"Camellia - Backbeat Maniac"** *(Mapped by: Evening)*

At its current state, you should be able to play the majority of your favorite SV/Gimmick maps. There are still improvements being done on this to add support for other types of out of the ordinary gimmick maps.


### Timing Bar Lines

Something that was missing from Quaver for ages were timing bar lines. This is now added into the game. 

### Performance Improvements

Quaver's gameplay screen has/is also recieving some performance improvements due to a new type of object pooling system Staravia is implementing. **FPS rates have reportedly increased from ~750 to ~1.2k (~40% improvement) on his machine.** Hooray for performance!

### Score Submission

Score submission also works properly! Whenever you're logged into the Quaver server, you're able to submit scores, and they'll be automatically processed, and you'll receive your updated stats and ranks (global & country). This also comes with the ability to check out scoreboards in-game during song selection.

# Quaver Libary Updates

<p align="center">
  <img src="https://i.imgur.com/KKt0H6x.jpg">
</p>

As many of you probably don't know, we've also been building up a C# library separate to the game client that has all things a third-party developer could need related to Quaver. It contains things such as map and replay parsing, difficulty calculation, scoring, and a ton of other helper classes and enums related to Quaver. This is the very same library that's used within the game client, so that means if we ever update anything, you'll have everything! Our main goal with this is to provide an easy way for developers to create external tools and to also provide a streamlined way to help out with Quaver's development.

## Accuracy System Updates

The main change in this area is that last month, Staravia decided to experiment with a new type of accuracy system for Quaver. 

In our previous system, when hitting an object, the weight accounted for accuracy was solely based on which judgement was received. That means if you hit an object with a 43ms deviance and another object with a 50ms deviance, they would be accounted for the same amount of weight because the hits are within the `Perfect` judgement window. 

However with this new proposed system, it is based on raw acccuracy in conjunction to a hit's associated judgement window rather than solely judgements themselves. Here's how it works:

<p align="center">
  <img src="https://i.imgur.com/S7IeS76.png">
</p>

The amount of weight an individual hit is accounted for is **determined by the deviance of the hit received on an object in accordance to its asscoiated judgement window.** The only exception to this is the `Marvelous` judgement where if you hit within its window, it is counted as 100%. Because of this system change, **it ultimately makes 100% scores only achieveable by getting a MFC (Marvelous-Only Full Combo).** It is also important to note that hit deviances are rounded down by 4ms, and you can see this in the graph above. Each vertical line represents the individual judgement window, and the main curve represents the amount of weight assigned to that given hit deviance.

Here is the equation used in its calculation:

<p align="center">
  <img src="https://i.imgur.com/BMrDbu6.gif">
</p>

Note: x is a value between 0 and 1 that is inside the marv and hitMiss domain.

The reason we've decided to experiment with this type of system is because **accuracy is a major and important aspect in how Quaver will be played.** With this type of system, we're able to reward players more for being accurate, and the performance of plays is considerably easier to measure with this type of system rather than the former. From our experience, it seems to play fairly well and gives precise accuracy% results based on the overall quality of the play. As always, there's always room for change and improvement in the early stages of the game's life.

# Quaver API & Web Updates

<p align="center">
  <img src="https://i.imgur.com/1OIdLaN.jpg">
</p>

In addition, [@AiAe](https://github.com/AiAe) and I have been beginning work on the front-end of our website and back-end API. With the alpha release, we're aiming at having a working website where you can view user profiles, leaderboards and maps. 

## Website

AiAe has been working super hard on developing the front-end of our website. It is currently being built in the popular JavaScript framework [Vue.js](https://vuejs.org/), and so far I'd say it looks pretty good.

### Profile Pages

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/OYyxb2O6oNY" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

---

Currently AiAe has been working on putting together probably one of the most frequently viewed pages - the profile page. This page shows information about an individual user such as who they are, where they're from, their rank/scores for each game mode, their uploaded maps, and a bunch of other data related to the user. This is still a work in progress, but we've decided to show you the current work that's being done on it so far. If you have any suggestions of things that you'd like to see on profile pages, tweet us [@QuaverGame](https://twitter.com/QuaverGame)!

## API

In addition to the website, I've also began work on developing the back-end API for Quaver. This part of the project is responsible for handling mapset & score submission, fetching data, and making authenticated requests to add/update/delete data. Here's what we've got so far:

### Mapset Submission

Players are now able to upload and update mapsets by making an authenticated request to our API server. When uploading, mapsets are automatically added to our database and sent to our storage servers. In light of this, we're able to put individual maps or sets in whichever ranked status we choose.

### Score Submission

As mentioned before, we've also implemented score submission both on the client and on the API. In-game, after play completion, scores and replays are automatically sent to the API server for submission. This process handles score and replay validation, and updating global and country ranks + leaderboards if successful.

### API Endpoints

In light of now having working mapset and score submission, I've also began implementing some API endpoints for the front-end of our website to use. With the current implemented endpoints, you can receive the following data about users and maps on our test server:

**Please note that this is just test server data. It should not be used for any applications at this time. These endpoints and data retrieved from them are bound to change at any time.**

#### Users

Here's all the currently implemented endpoints related to obtaining user information:

• **[/users/full/:id](https://tsapi.quavergame.com/v1/users/full/3)** - Obtain full user information for a given player. Receive information such as their username, id, usergroups and privileges, and their current stats and ranks.

• **[/users?id=&name=](https://tsapi.quavergame.com/v1/users?id=3&name=test1)** - Obtain non-full information about multiple users at a time.

• **[/users/search/:name](https://tsapi.quavergame.com/v1/users/search/sw)** - Find users by a given search term

• **[/users/scores/best?id=&mode=](https://tsapi.quavergame.com/v1/users/scores/best?id=3&mode=1)** - Retrieve a user's best (top play) scores by a given game mode.

• **[/users/scores/recent?id=&mode=](https://tsapi.quavergame.com/v1/users/scores/recent?id=3&mode=1)** - Retrieve a user's recent scores by a given game mode. This includes non-top play and failed scores.

---

#### Mapsets/Maps

Here's all the currently implemented endpoints related to obtaining mapset information:

• **[/mapsets/:id](https://tsapi.quavergame.com/v1/mapsets/7)** - Obtain full information about an entire mapset.

• **[/maps/:id](https://tsapi.quavergame.com/v1/maps/16)** - Obtain information about an individual map.

---

#### Scores

Here's all the currently implemented endpoints related to scores.

• **[/scores/map:id](https://tsapi.quavergame.com/v1/scores/map/18)** - Obtain all top scores on an individual map.

---

#### Server

Here's all the currently implemented endpoints related to our server:

• **[/server/users/online](https://tsapi.quavergame.com/v1/server/users/online)** - Retrieve a count of the number of users that are currently online.

• **[/server/users/online/:id](https://tsapi.quavergame.com/v1/server/users/online/4)** - Check if an individual user is connected to the server.

All in all, more endpoints are being implemented as more data is being stored for Quaver. We plan to have proper API documentation in the future as we start to solidify some of our endpoints.

# Conclusion

<p align="center">
  <img src="https://i.imgur.com/93Vk2nu.jpg">
</p>

Phew! That was a lot of writing. If you've made it this far, thanks for reading! As the new season is here, we're beginning to work extremely hard on completing things on time to release an alpha version within the next 1-2 months. There's still a lot to do before releasing and open sourcing the game can happen such as getting our Steam store page situated and also polishing up our game further. Thanks a ton to everyone who has been riding with us thus far, and it has been an absolute pleasure seeing the amount of hype and positivity surrounding what we're trying to accomplish with Quaver. 

As always, if you're interested in keeping up-to-date with what's happening outside of the blogs, you can join our [Discord Server](https://discord.gg/nJa8VFr) and give us a follow on Twitter [@QuaverGame](https://twitter.com/QuaverGame). Until next time!
