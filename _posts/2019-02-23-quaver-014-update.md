---
layout: post
comments: true
title: Quaver v0.14 - The Editor, Ranking Criteria, New Mods & Much More!
thumbnail: https://i.imgur.com/dDRdFOP.jpg
author: Swan
short_text: Hey, friends! We're back and have just released version 0.14 of Quaver, and it is by far our BIGGEST update yet! This time around, we've implemented a map editor, ranking criteria, Windows 7 & Linux Support for Steam, new game modifiers, and so much more! This update definitely marks the turning point for Quaver...
---

Hey, friends! We're back and have just released version 0.14 of Quaver, and it is by far our **BIGGEST** update yet! This time around, we've implemented a map editor, ranking criteria, Windows 7 & Linux Support for Steam, new game modifiers, and so much more! This update definitely marks the turning point for Quaver, and we're very excited for the future!

# Alpha Tester Program Updates

<p align="center"><img src="https://i.imgur.com/QArWtOE.jpg"></p>

At the time of the initial alpha release, we decided to give randomly selected testers a chance to get small taste of what Quaver has to offer in terms of its online capabilities. After 2 months with around 275 testers, we learned a ton about how we want to begin running the game in most aspects. It took a ton of time, but we wanted to make sure we were prepared before moving forward with the game.

### Ranking Process & Criteria

One of the biggest challenges that we've faced throughout this initial testing period was figuring out how to have a structured ranking process while still keeping it fairly lenient. Our main goal is to allow all users to have an equal opportunity to have their mapsets considered for rank without too much of a hassle. Throughout this time, our team had a meeting discussing what we would like the future of ranking system to look like, and it proved to be very useful.

Because of this, in January we've made the decision to pause the ranking of new mapsets until we had a solid ranking criteria/process and the map editor was released.

We now have a proper [Ranking Criteria](https://quavergame.com/wiki/Ranking/Criteria) and [Ranking Process](https://quavergame.com/wiki/Ranking/Process) that you can check out on our website's wiki. If you're a map creator, be sure to submit your maps for rank! From this point on, we're continuing ranking, and you'll have a ton of new maps to compete on.

### Didn't Get Your Steam Key Yet?

No worries! Over the next week or two, everyone who signed up will receive their alpha key via email. We intentionally put a pause on accepting new users into the alpha tester program until this update was released.

### Next Alpha Sign Up

If you didn't get a chance to sign up for the alpha initially, you're in luck. After we accept all the current sign ups, we plan on opening up registrations for the alpha once more to welcome new testers.

---

# Game Client Updates

<p align="center"><img src="https://i.imgur.com/khsSx1F.jpg"></p>

As always, the bulk of the updates is for the game client. We've got a **TON** of exciting updates for you guys to check out including the editor, Windows 7 & Linux support, new modifiers, and more skinnables! Let's get going!

**Alpha Testers**

Restart your Steam client, and the game will automatically update for you.

**Non-Alpha Testers**

You can grab the latest version of the game on [GitHub](https://github.com/Quaver/Quaver/releases/tag/0.14.0), but you will not be able to access any online features.

## The Editor

One of the biggest features that was missing from Quaver was a map editor. Previously, players had to rely on third-party tools or games  in order to create content for Quaver. While this was sufficient when just beginning the game, the release of Quaver's editor is definitely a turning point since this reliance is no longer needed. 

This editor took around a month and a half to develop and is loaded with a ton of features and customizables. Here's we've got in store for you:

### Layers - A New Way to Create!

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/bT4DpCm9H0Q" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>
---

With Quaver's editor, we've introduced an entirely new way to create, structure, and think about maps. It's called **Layering.**

With this feature, you're able to group objects with a layer name and color which can ultimately help with mapping objects to individual sounds in the music. An example of this would be if you wanted to group objects that represent a kick sound in the music and another group that represents clap sounds. 

You're able to toggle the visbility of layers, so you can easily see and hear hitsounds for those objects alone. This makes it easier to make sure your maps are designed in a well manner.

Given that objects can be grouped into layers, it is now only one click to apply hitsounds to all objects in that layer as well as deleting them. 

This is definitely a great feature to have and it's relatively unique. The idea is based on a common chart structuring technique/idea, so we're excited to see how everyone makes use of it.

### Customizability

<p align="center">
  <img src="https://i.imgur.com/BAIrygI.png" width="300px" height="168px">
  <img src="https://i.imgur.com/7vNBRw3.png" width="300px" height="168px">
</p>

We realize that the majority our players come from already existing rhythm games. One of the main goals of Quaver is to provide a familiar experience for seasoned rhythm game players by taking the best concepts from our predecessors while expanding upon them and combining them into one "ultimate" game. The editor is no different. We built it with customizability in mind, so no matter which game or editor you come from, you can feel right at home in little time with Quaver's.

Notable customizables/features include: 

* • The ability to use either a mouse or keyboard as input for the editor
* • Customizable beat snap colors (supports colors from most major games)
* • Easy support for both bar and arrow skins within the editor
.
### Realtime Difficulty Calculation

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/FnaGMs8G-sA" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>
---

One thing we've noticed that alot of editors lack is the ability to see how difficult a map is in its respective game while you're in the editor. With this feature, the difficulty of the map is recalculated whenever you make changes, so you have an idea of how difficult the map is without any hassle.

### Hot Reloading

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/NRvBDyaijbQ" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>
---

Another cool feature of this editor is the ability to modify the .qua file of your maps while editing. In some circumstances, this may be necessary for people, so we've made it so it will detect any outside changes to the .qua file and ask you to reload the map while editing.

### Mapset Uploading & Updating

If you're an alpha tester and have tried to upload your creations, you'll know that it wasn't incredibly easy to do so on our website. We've now removed the upload feature from our website and have limited uploading and updating mapsets to ingame only.

### Crash Autosave

As we're sure there will be a ton of bugs with the editor, we've gone ahead and implemented crash autosaving. If/Whenver the game crashes while editing, it will try to save your map in its most recent state. Upon relaunching, the game will ask you if you'd like to reload the editor with your previous work. 

Developed by [Swan](https://github.com/Quaver/Quaver/pull/507).

---

## New Game Modifiers

We've also added a ton of new modifiers for you to try out including Inverse & Full LN, half rates (.x5), and Mirror.

### Inverse & Full Long Note Modifier

<p align="center">
  <img src="https://i.imgur.com/Kt481A1.jpg" width="300px" height="168px">
  <img src="https://i.imgur.com/SqGGdMg.jpg" width="300px" height="168px">
</p>

In addition to "No Long Notes", we've also implemented "Inverse" and "Full LN" modifiers. These essentially act as the reverse of No Long Notes where they make the map entirely of LNs. However, they do have some differences.

**Inverse**

Turns existing normal notes into long notes and removes original long notes - creating a gap.

**Full LN**

Turns all normal notes into long notes.

Both of these modifiers are strictly for practice and will not be counted for global rankings.

Developed by [YaLTeR](https://github.com/Quaver/Quaver/pull/544).

---

### Mirror

<p align="center">
  <img src="https://i.imgur.com/gpsjzaL.jpg" width="300px" height="168px">
  <img src="https://i.imgur.com/qLDgNAz.jpg" width="300px" height="168px">
</p>

With this modifier, the game will flip the map horizontally which mirrors the original. 

Using this modifier will count towards global rankings.

Developed by [Swan](https://github.com/Quaver/Quaver/pull/545).

---

### Half Rates

We've also added more speed rates to play with. From 0.5x-1.0x, we've added half rates. You can now play at speeds of 0.55x, 0.65x, 0.75x, and so on. There are now an equal amount of slower rate modifiers are there are faster rates.

Using these modifiers will count towards global rankings.

Developed by [YaLTeR](https://github.com/Quaver/Quaver/pull/525).

---

## More Things to Skin!

As with every update, we're always adding more ways to customize the game. This time around we've added Lane Covers, Combo Alerts, and much more!

### Lane Covers

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/AcBJLeRd_XQ" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

[Song Credit: Our Stolen Theory - United (L.A.O.S Remix)](https://www.youtube.com/watch?v=rnWXN8m6drc)

We've now made the process of creating, using, and customizing lane covers so much simpler. You're now able to create lane covers for both the top and bottom of the playfield, as well as adjust their sizes and the options menu.

Developed by [Sublimity](https://github.com/Quaver/Quaver/pull/529).

### Combo Alerts

<div style="width:100%;height:0px;position:relative;padding-bottom:56.250%;"><iframe src="https://www.youtube.com/embed/O7C29SOAnn8" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;"></iframe></div>

[Song Credit: Hyper Potions - Ski](https://www.youtube.com/watch?v=e_s00Hfo4VA)

In addition, we've now implemented combo alerts. Whenever your combo reaches multiples of 100, a sound effect and image will be played. You have the liberty to add as many sound effects and alert images as you'd like!

Developed by [Swan](https://github.com/Quaver/Quaver/pull/551).

### Judgement Counter

You can now completely customize the judgement counter including turning it off completely. You're now able to change its image, color, font color, and size.

Developed by [Swan](https://github.com/Quaver/Quaver/pull/553).

### Song Time Progress

You can now customize the colors of the song time progress bar along with disabling the numbers if you choose to. This should be useful if your custom skin is trying to match a certain theme.

Developed by [Swan](https://github.com/Quaver/Quaver/pull/554).

---

## Windows 7 & Linux Support

<p align="center"><img src="https://i.imgur.com/X9eexz5.png" width="300px" height="168px"> <img src="https://i.imgur.com/0JZ6Kx9.jpg" width="300px" height="168px"></p>

Previously, Quaver had a few compatibility issues with Windows 7 and Linux. These have now been identified, fixed and are now available on Steam.

---

## More Additions

* • Show progress when importing mapsets ([Staravia](https://github.com/Quaver/Quaver/pull/492))
* • Pause Screen Navigation ([Staravia](https://github.com/Quaver/Quaver/pull/514))
* • Add a linux launch script ([YaLTeR](https://github.com/Quaver/Quaver/pull/520))
* • Add TimingLineColor to skin.ini ([YaLTeR](https://github.com/Quaver/Quaver/pull/523))
* • Misses on the hit difference graph are larger & LN releases are shown correctly ([YaLTeR](https://github.com/Quaver/Quaver/pull/526))
* • Always draw border around hit difference graph ([YaLTeR](https://github.com/Quaver/Quaver/pull/543))
* • Add setting to skip results screen after quitting ([YaLTeR](https://github.com/Quaver/Quaver/pull/552))
* • Add keybinds for navigation ([Staravia](https://github.com/Quaver/Quaver/pull/556))
* • Add DrawLongNoteEnd to skin.ini & fix object positioning ([YaLTeR](https://github.com/Quaver/Quaver/pull/560))

---

## Bug Fixes

* • Fix time progress not showing the correct time for rates ([Staravia](https://github.com/Quaver/Quaver/pull/506))
* • Scale the timing windows back to 1.0x rate for the hit difference graph ([Staravia](https://github.com/Quaver/Quaver/pull/518))
* • Fix skipping to far on SV maps ([YaLTeR](https://github.com/Quaver/Quaver/pull/519))
* • Fix SV Issues ([YaLTeR](https://github.com/Quaver/Quaver/pull/536))
* • Fix multiple audio tracks being played ([Staravia](https://github.com/Quaver/Quaver/pull/563))
* • Fix progress display showing -00:00 before the track starts ([Staravia](https://github.com/Quaver/Quaver/pull/564))
* • Fix Long Note ends not being hidden on time ([YaLTeR](https://github.com/Quaver/Quaver/pull/564))

---

# Conclusion

<p align="center"><img src="https://i.imgur.com/6XhLmbn.jpg"></p>

## What's Next?

If you were wondering what's next on our priority list, it's the overall goal of getting Quaver in a state where it is available for public early beta access on Steam. With this, we have a few more features that need to be added before this is able to happen.

### Multiplayer

The next big feature on the list is multiplayer. We have a ton of new ideas for multiplayer that we're looking at implementing, so stay tuned on this.

### Complete UI Redesign

Before we release a public early access version of Quaver on Steam, we'll be looking at completely redesigning the game's UI and website from the ground up to give Quaver a fresh look.

Thus far, we've developed the game with features as our priority rather than design. We wanted to find out what features are needed from all of our testers in their ideal version of a VSRG. This proved to be very useful. Because we now have an idea, we can begin to redesign the game to give Quaver more of an identity. 

After this has been developed, the game will be released in public early access on Steam for everyone to try out.

## Final Words

As always, if you've made it this far, thanks for reading! This blog post was long but rich in content. We're extremely excited for the future of Quaver, and this is only the beginning. As always, make sure to report any bugs or request any features on [GitHub](https://github.com/Quaver/Quaver). 
