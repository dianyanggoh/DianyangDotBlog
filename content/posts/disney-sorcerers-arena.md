---
title: "Game Notes: Disney Sorcerer's Arena"
date: 2020-03-29T11:35:45+08:00
draft: false
tags: ["game notes","game design","combat","ui"]
---
I tried [Disney Sorcerer's Arena](https://www.sorcerersarena.com/) and really liked its streamlined combat, particularly the persistent target selection. When combat begins, an enemy target is selected by default. Players can switch target anytime, but otherwise the target remains the same each turn. This saves players an extra click most of the time when they perform an action, since the optimal strategy in most cases is to focus fire on one enemy anyway. (AOE actions hit all enemies instead of a subset of enemies, so targeting is skipped.)

It seems like a small thing but now most turns require only ONE input, which is the absolute minimum number of interactions. Filing this under [Oil it or spoil it](https://www.gamasutra.com/blogs/LarsDoucet/20160810/279009/Oil_it_or_Spoil_it.php). (For similar reasons, combat in Pokemon should probably persist the active menu instead of resetting to the top level at the start of each round. Most of the time you're probably choosing a combat action anyway, instead of using items or switching Pokemon or fleeing.)

This system does not work if targeting is more nuanced(e.g. AOE actions affect only a small area, heals or buffs that target single party members, etc). You could have the game dynamically default to the target that makes the most sense for a given action, but then players would have to first select the action, make sure the default target matches their intention, then confirm the action. I suspect there might be workarounds, but they will probably be either clunky or confusing for players.

I think sacrificing a little extra depth for a huge usability gain is often worth it. 

Eventually, I unlocked the auto-battle option. One input is not the minimum number of interactions after all.

P.S. Somewhat surprisingly, the game features a dynamic turn order system. Maybe that should be the subject for another post.
