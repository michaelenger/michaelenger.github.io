---
title: The Mac Needs Proton
description: As a frustrated "Mac Gamer" I desperately wish Apple would just concede the fight and work with Steam to make Windows games work better on macOS.
date: 2023-12-16
---

I have a confession to make. I am a Mac Gamer™. Or I guess more accurately, I want to be. I use an iMac as my main computing device, for a myriad of reasons that are irrelevant to the current discussion, and I would _love_ to be able to game on it as well. It's getting a bit old (I have the 21.5-inch Retina model from 2017), but it's fully capable of playing the types of games I like, mostly games from the mid-to-late 2000s. However, it's unable to run those games because Apple refuses to play nice.

## The Mac Gamer's Timeline of Disappointment

### September 2003

[Steam](https://store.steampowered.com/), the digital marketplace for PC games, is released, heralding a new future of digital distribution. As much friction as it caused when it first came out, this was an inevitability that the world has embraced and it honestly made gamers' lives better.

### June 2007

The original iPhone is released which transforms Apple into one of the biggest companies in the world. Steve Jobs was doing well with dragging the company out of the gutter, but the launch of the iPhone resulted in explosive interest in Apple and in Macs from people who were previously disinterested.

### July 2008

The App Store is opened and there is a gold rush for app and game developers who all want to capture this new, absolutely massive, market. This is around the time when I got my first MacBook, inspired to make my own mobile game. This plan of course goes nowhere.

### May 2010

Steam is available on macOS! The wide adoption of Macs has caught the eyes of game developers who are toying with porting their PC games to the platform. Valve, ever ready to facilitate digital distribution, jump on the chance to make it easier for both developers and gamers to embrace this new world. Although there is only a subset of developers who are taking advantage of this new market I still consider this is the start of the good times.

![Screenshot of Steam running on macOS. Credits to Federico Viticci at MacStories](/assets/blog/steam-mac.jpg)

### January 2011

The Mac App Store is launched. I doubt this was done as a response to Steam coming to macOS, but Apple at least are trying to make discovering new apps (and games) easier for their Mac users. They also want that sweet 30% cut, of course.

### February 2013

Steam is available on Linux, for some reason? This felt like a "sure, why not?" move at the time, but in hindsight it was a telltale sign of things to come. Valve had started to experiment with building their own hardware and released the Steam Machine later that year to a lacklustre response. Nobody was impressed and macOS was still considered the main "sibling" platform to Windows with macOS versions of game coming now and then, mostly from indie developers.

### June 2019

Apple announces Mac Catalyst, a set of tools and libraries meant to make it easier to port iOS apps to macOS. It allows you to add support for platform-specific features or UI paradigms, but still maintain a single codebase. In essence have a single app for multiple platforms, the start of a trend where the iOS and macOS platforms are seemingly merging.

### October 2019

macOS Catalina is released and with it comes a dagger through the heart of Mac Gamers. Despite being deprecated for many years, this was the release which officially dropped support for 32-bit applications completely. Upgrading to Catalina meant that you lost the means to play 90% (if not more) of the games on Steam that claim to support macOS.

Developers are encouraged to update their games to 64-bit, but for many it doesn't make sense to put in the effort for a small subset of users. This was, after all, not their fault... it was Apple who had decided that backwards compatibility was too much hassle. This move kills Mac gaming almost outright with many people, myself included, having their game libraries decimated.

### November 2020

Apple releases the M1 chip, an ARM-based processor meant for the new generation of Macs. They are officially moving away from using regular x86-64 processors provided by Intel to their own developed chips that are similar to the A1 chips used in iPhones and iPads. The chips are a great success and blow the old architecture out of the water in all the benchmarks... while also bringing the iOS and macOS platforms even closer together.

### February 2022

Valve releases the Steam Deck which does what the Steam Machine couldn't. This device is moderately priced, has a form factor reminiscent of the Nintendo Switch, and has just enough computing power to play most of the games people want to play. It is a runaway success and singlehandedly kickstarts a wave of handheld PC gaming devices.

![A promo photo of the Steam Deck.](/assets/blog/steam-deck.jpg)

However, the one key factor that most of Valve's competitors are unable to replicate is Steam OS, the bespoke Linux-based operating system that runs on the Steam Deck. Leveraging their experiences with the Steam Machine, Valve essentially built their own Linux distribution which is really good at running Steam and the games purchased through it. To maximise support for the game libraries that people have been building since 2003 they've made enhancements to [Wine](https://www.winehq.org/), a compatibility layer meant to let you run Windows applications under Linux. This new Wine fork is called Proton and with its integration into Steam it works so much better than anyone could've expected.

Mac Gamers stand on the sidelines, jaws agape in disbelief, as the majority of games released on Steam suddenly "just work" on Linux.

### June 2023

Apple, perhaps realising that they've lost a lot of ground in the lucrative gaming market, releases [Game Porting Kit](https://developer.apple.com/videos/play/wwdc2023/10123/). This is a set of tools meant to help developers port their Windows games to macOS, by for example converting their DirectX pipeline to Metal and making the game run natively on the M1 architecture. In an effort to seem serious they even brought [Hideo Kojima on stage at WWDC](https://www.theverge.com/2023/6/5/23749698/apple-mac-os-death-stranding-directors-cut-hideo-kojima-wwdc-2023) to talk about how Death Stranding, a AAA video game originally released in 2019, is coming to the Mac.

There was a flurry of activity around this new porting kit, with developers digging into it to find out how it works... and turns out it's just like Valve's Proton. Apple have forked Wine and added a bunch of their own features and fixes on top of it, then wrapped the whole thing into a _Kit_ meant for testing and debugging games. People of course don't care about any of that and immediately start trying to find ways to just play their games using it.

### February 2024 ([Announced](https://help.steampowered.com/en/faqs/view/743F-2E0E-C9A5-C375))

Steam is planning to drop support for macOS High Sierra and Mojave, the last macOS versions which supported 32-bit apps. If the release of macOS Catalina was Mac Gamers getting stabbed in the neck, this is the last shovelful of dirt hitting the grave.

## Aftermath

So here we are... the macOS platform has grown massively in the past decade and a half, much like the gaming market. Valve saw where things were going and attempted to get in on the action, but it seems like Apple weren't really interested in fostering gaming on Mac. They want to focus on iOS and have even taken steps to move their desktop platform in that direction. It wouldn't surprise me if we see them merging the operating systems at some point in the future.

However, as much as I am bitter about not being able to use my Mac to game on, there is nothing irrational about Apple's decisions. The ridiculously lucrative mobile gaming market is a place where Apple is in the lead, so why would they want to fight with Microsoft for the attention of the fickle and legendarily toxic Real Gamers™? As long as the majority of people want to play casual games on their phones and Apple can keep skimming off the top of all those  sweet microtransactions they have no reason to change their priorities.

But something has seemingly changed. Apple have clearly realised that there is a lot of money to be made off desktop gaming and they have made moves to seemingly make macOS a more gaming-friendly platform. However, in classic Apple fashion they have decided that instead of making their operating system better at playing existing games, they're going to incentivise people to jump into their walled garden.

![A photo of Hideo Kojima from the WWDC 2023 presentation. It is subtitled with the text 'I have been a die-hard Apple fan since I bought my first Mac back in 1994.'](/assets/blog/hideo-kojima-wwdc.jpg)

My impression is that everyone knows that this move by Apple isn't going to actually change anything and nobody is really interested in porting their games. Hideo Kojima will take their money, hire some 3rd party company to port the game, and go off to [hang out with celebrities](https://youtu.be/M0tmk5lJOSs) without a care in the world. And the gamers have already found a way to extract the innards of the Game Porting Kit and turn it into an app which can run Windows games, cheekily named [Whiskey](https://getwhisky.app/). Apple lost everyone's trust when they cut us off from our gaming collections and developers aren't impressed with these new shiny new shackles.

As of this writing Death Stranding has yet to be released for macOS.

## What The Mac Needs

If Apple want people to game on Mac they need to go to where gamers are. The kind of person who is interested in playing intense, engrossing games and building a large gaming library already has. They did it on Windows, probably via Steam, and have dozens, if not hundreds, of games that they don't want to lose access to by moving to a different platform.

Allowing gamers to make use of their existing libraries is exactly what Valve did, and based on the runaway success they've had with the Steam Deck one can say that it has paid off for them. I don't have a Steam Deck (yet) but I've installed Linux on an old laptop and I can tell you Proton works like an absolute charm. Some games require a bit of tweaking, but there is a [readily available database of fixes](https://www.protondb.com/) and most of the time it's just a matter of choosing the correct Proton version.

Developers don't really have an incentive to port their games to macOS when the market is a fraction of what it is on Windows. And gamers aren't going to choose Macs since they know that the games they already have won't work there. Now if someone wants an alternative to Windows they can even choose Linux for an (almost) turnkey experience, so what does the Mac have to offer? The Game Porting Kit could easily have been open-source contributions to Wine, and I bet you that Valve would love to be able to turn on their compatibility layer on macOS. If Apple were actually serious about supporting gaming in Mac they'd find a way to make it work.

But of course they won't.

I am completely aware that the reason Apple would rather incentivise developers to join them in their exclusive club rather than go to where people are is because there's no money in it. They aren't actually interested in making macOS a good platform for gaming, they want people to spend more money in the Mac App Store. Adding improvements to Wine and partnering with Valve to make Proton work as seamlessly on macOS as it does on Linux wouldn't let Apple see it's 30% cut. Making the macOS platform attractive to a wide range of users who will then buy their pricey hardware isn't as lucrative as getting their existing Mac owners to spend more on apps. People just [don't buy computers like they used to](https://gagadget.com/en/business/233842-global-pc-market-collapses-29-in-early-2023-apple-fared-worst/) so now it's all about getting people to pay monthly for add-on services and buying microtransactions ([which they do](https://www.techspot.com/news/48412-study-91-of-mobile-game-revenue-comes-from-microtransactions.html)).

Gaming on Mac is languishing and that makes me sad.
