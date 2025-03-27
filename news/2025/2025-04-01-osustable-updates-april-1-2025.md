---
layout: post
title: "osu!(stable) Updates: April 01, 2025"
date: 2025-04-01 19:00:00 +0000
---

A relic of the past is finally being updated to modern standards!

![](/wiki/shared/news/2025-04-01-osustable-updates-april-1-2025/banner.jpg)

For as many efforts from the osu! developers have been put into making osu!(lazer) the best version of osu! to date, it is hard to deny that a good chunk of the community is still stuck in the old client. This is clearly evident by the data shown in the graph below, showing the amount of users between the two clients throughout 2024:

![](/wiki/shared/news/2025-04-01-osustable-updates-april-1-2025/look-at-this-graph.jpg)

So worry not — we hear you! In the following post, we'll go over some new changes **coming to both osu! and osu!(lazer)** in the hopes of bringing a glimmer of light to a once thought to be feature-locked client! Nobody is getting left behind.

## Updates

The following assortment of changes will be coming to all platforms. Stable, osu!(lazer), and the osu! web will all be impacted by these changes unless stated otherwise. Given the impact of some of these changes, we've decided to slowly roll them out.

Over the span of **1.9904179 years**, users will be given the option to update to the latest version of the game. Based on community feedback, some of these features will not see the light of day on later deployments.

### Editor

- **The session may be terminated if [BanchoBot](https://osu.ppy.sh/users/3) dislikes the map.** This will ensure a minimum level of quality for all maps being uploaded to the platform. Moreover, BanchoBot's very reasonable standards will force mappers to learn, else they risk losing access to the editor.
- **Map previews have been removed.** Users will be met with a brand new osu! Integrated Development Environment (o!IDE) where they'll be able to manually edit their beatmaps from `.osu` files instead.
- **Objects will not be able to be placed on coordinates with prime numbers.** We believe prime numbers are only really useful on [public-key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) and have no place in a rhythm game like osu!. Mappers can find a comprehensive list of banned numbers [here](https://www.mathematical.com/primelist1to100kk.html). Any object placed on a banned coordinate will cause the game to crash and any progress, saved or unsaved, will be lost.

### Gameplay

- **A new type of note has been added to osu!taiko.** As previously spoiled by [Pentaclar](https://x.com/bladeepolska/status/1903423461042561120), these notes will randomly appear on the playfield and will instantly fail the player if they had the misfortune to encounter one.
- **The Relax mod will award performance points.** Many players have requested the ability to submit their scores and be awarded for them. While it will come with a hefty penalization, this will allow players from all skill ranges to compete even on the hardest of beatmaps!
- **osu!mania will only allow horizontal scroll moving on.** This will allow players to more easily transition between osu!taiko and osu!mania, as both rulesets would share similar reading skills.

![](/wiki/shared/news/2025-04-01-osustable-updates-april-1-2025/mania-playfield-comparison.jpg)

- **HP has been removed.** osu! has always been seen as a "combo game", where a player's consistency was often the most important factor in how well they'd perform. Therefore, all game modes will have their HP removed, and any miss will instantly cause players to fail. No need to use Sudden Death anymore!
- **Rates now award performance points — with a catch!** Only *downrates* are affected by this change. Any rate between 1.0x and 1.5x or above will not be eligible for it.

### Other

- **osu!taiko will no longer be a rankable ruleset.** Given its dwindling player engagement, the team will be focusing on the rest of game modes until Hivie looks into it tomorrow.
- **Micro-stutters have been added as an official feature.** To level the field between players, the game will now automatically add stutters on players who far surpass the game's minimum and recommended requirements. This will allow players from all hardware generations to compete under a similar set of conditions.
- **A new GitHub post leaderboard has been added.** Users who link their GitHub accounts, will automatically join the brand-new GitHub post leaderboard. Players will be able to tally the amount of posts, pull requests, discussions, and issues they participate in. This will encourage users to interact with the game's development, gaining some performance points in the process for every successful contribution.
- **Removed Herobrine.**

## Project Hated

![](/wiki/shared/news/2025-04-01-osustable-updates-april-1-2025/project-hated-banner.jpg)

Due to popular demand, on top of announcing the previous suite of changes coming to the game, we'd like to premiere [**Project Hated**](https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUXbmV2ZXIgZ29ubmEgZ2l2ZSB5b3UgdXDSBwkJvQCDtaTen9Q%3D)! From now on, users will be able to vote their less-than-favourite maps to get **permanently removed** from the Loved section.

While the team believes [Project Loved](/wiki/Community/Project_Loved) has been a very successful and well-liked project, by constantly adding new maps the Loved section has grown itself too much for its own good. By removing beatmaps the community doesn't *love* anymore, the Loved section will iteratively be curated with each passing month. Ultimately, in a few years time, each game mode's Loved section will be the best version of itself it could ever be!

Can't get a full combo score on a map? No problem! Thanks to Project Hated, if you can't, nobody else will once the leaderboards are removed.

---

So, what are you waiting for? Make sure to give [osu!(stable)](https://m1.ppy.sh/r/osu!install.exe) and [osu!(lazer)](https://github.com/ppy/osu/releases/latest/download/install.exe) a try! The more active a player is, the quicker they'll be prompted to update their game.

For those interested in osu!(lazer) exclusive updates, please check [last week's update](https://osu.ppy.sh/home/news/2025-03-23-osulazer-updates-march-21-2025) news post. While it stable may not get any more updates moving on, rest assured for osu!(lazer) will be getting them in its stead!

—0x84f, RandomeLoL & Walavouchey
